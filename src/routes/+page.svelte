<script>
    import { hello } from '$lib';
    let counter = 0;

    hello();
    $: setTimeout(() => (counter += 1), 400);
</script>

<h1>{counter}</h1>

<style>
    * {
        background-color: red;
    }
</style>
