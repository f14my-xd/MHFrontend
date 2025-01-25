<script>
    import Header from "../header.svelte";

</script>

<section>
    <Header></Header>
    <div class="Main">
        <div class="MainText">Тарифы</div>
    </div>
</section>

<style>
    .Main {
        display: flex;
        justify-content: center;
        margin-top: 10vh;
        flex-direction: column;
        align-items: center;
    }

    .MainText {
        font-family: "Inter", serif;
        font-size: 34px;
        font-weight: 300;
    }
</style>