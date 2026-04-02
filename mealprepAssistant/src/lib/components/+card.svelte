<script lang="ts">
    let { children , title, subtitle = ""}: { children: any, title: string, subtitle?: string} = $props();
    
</script>

<div class="flex flex-col bg-gray-400 rounded-xl shadow-xl m-2 p-2">
    <div>
        <h1 class="font-bold text-2xl">{title}</h1>
        <h2 class="text-gray-600 text-sm">{subtitle}</h2>
    </div>

    <div>
        {@render children()}
    </div>
</div>