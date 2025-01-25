<script>
    import Header from "../Header.svelte";
</script>

<svelte:head>
	<title>Регистрация</title>
</svelte:head>

<section>
    <Header></Header>
    <div class="RegisterForm">
        <div class="MainText">Вход</div>
        <div class="InputRow">
            <div class="InputColumn">
                <div class="InputView">
                    <div class="InputDesc">Логин</div>
                    <input class="Input">
                </div>
                <div class="InputView">
                    <div class="InputDesc">Пароль</div>
                    <input class="Input">
                </div>
            </div>
        </div>
        <button class="Button">Продолжить</button>
        <div class="MoreLink">
            <div class="LinkDesc">Нет аккаунта?</div>
            <div class="Link">Зарегистрироваться</div>
        </div>
    </div>
</section>

<style>

    .MoreLink {
        margin-top: 15px;
        display: flex;
        flex-direction: row;
    }

    .Link {
        font-family: "Inter", serif;
        font-size: 14px;
        font-weight: 300;
        color: #5e74ff;
        text-decoration: underline;
        }

    .LinkDesc {
        font-family: "Inter", serif;
        font-size: 14px;
        font-weight: 300;
        color: #656565;
        margin-right: 3px;
    }

.Button {
        width: 200px;
        height: 40px;
        font-family: "Inter", serif;
        font-size: 14px;
        font-weight: 300;
        color: #ffffff;
        background-color: #5e74ff;
        border: none;
        border-radius: 100px;
        transition: 0.5s;
        margin-top: 15px;
    }

    .Button:hover {
        background-color: #3550ff;
    }

    .InputDesc {
        margin-top: 10px;
        font-family: "Inter", serif;
        font-size: 14px;
        font-weight: 300;
        color: #000000;
    }

    .Input:focus {
        border-color: #a3a3a3;
    }

    .Input {
        outline: #5e74ff;
        border: 1px solid #E2E2E2;
        width: 400px;
        height: 45px;
        font-family: "Inter", serif;
        font-size: 16px;
        font-weight: 300;
        color: #000000;
        padding-left: 10px;
    }

    .InputColumn {
        margin: 10px;
        display: flex;
        flex-direction: column;
    }

    .InputRow {
        margin-top: 25px;
        display: flex;
        flex-direction: row;
    }

    .RegisterForm {
        display: flex;
        justify-content: center;
        margin-top: 15vh;
        flex-direction: column;
        align-items: center;
    }

    .MainText {
        font-family: "Inter", serif;
        font-size: 34px;
        font-weight: 300;
    }
    
    @media screen and (max-width: 480px) {
    .Input {
        width: 87vw;
        height: 42px;
    }
    }

    @media screen and (max-width: 860px) {
    .InputRow {
        flex-direction: column;
    }
    }

</style>