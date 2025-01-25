<section>
    <div class="Main">
        <div class="Logo">MyHost</div>
        <div class="HeaderBlock">
            <div class="HeaderLink">Главная</div>
            <div class="HeaderLink">О нас</div>
            <div class="HeaderLink">Помощь</div>
            <a href="/tarifs">
                <div class="HeaderLink">Тарифы</div>
            </a>
            <a href="/login">
                <button class="HeaderButton">Войти</button>
            </a>
        </div>
    </div>
</section>

<style>

    a {
        text-decoration: none;
    }

    .Main  {
        display: flex;
        justify-content: space-between;
        flex-direction: row;
        align-items: center;
        padding: 15px;
    }

    .HeaderBlock {
        display: flex;
        flex-direction: row;
        align-items: center;
    }

    .Logo {
        font-family: "Inter", serif;
        font-size: 28px;
        font-weight: 600;
    }

    .HeaderLink {
        font-family: "Inter", serif;
        font-size: 14px;
        font-weight: 300;
        color: #656565;
        margin-right: 18px;
        transition: 0.5s;
    }

    .HeaderLink:hover {
        color: #5e74ff;
        text-decoration: underline;
    }

    .HeaderButton {
        width: 150px;
        height: 40px;
        font-family: "Inter", serif;
        font-size: 14px;
        font-weight: 300;
        color: #ffffff;
        background-color: #5e74ff;
        border: none;
        border-radius: 100px;
        transition: 0.5s;
    }

    .HeaderButton:hover {
        background-color: #3550ff;
    }

    @media screen and (max-width: 590px) {
    .HeaderLink {
        display: none;
    }
    }

</style>