<script lang="ts">
import Card from '$lib/components/+card.svelte'
import NavButton from '$lib/components/+navButton.svelte'
</script>

<h1 class="flex justify-center mt-8 ">MealPrep Assistant</h1>

<!-- Login Box-->
<Card title={"Login"}>
    <form class="flex flex-col" method="POST">
        <label for="email">Enter your Email</label>
        <input type="email">

        <label for="password">Enter your Password</label>
        <input type="password">

        <input type="submit">
    </form>
</Card>

    <Card title={"Test"} subtitle={"Test2"}>
        <p>This is a child</p>
    </Card>

<NavButton content="Hello" nav="/">
</NavButton>