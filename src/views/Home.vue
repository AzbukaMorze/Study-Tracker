<template>
  <body class="body">
    <div class="wrapper">
        <header class="header">
            <div class="header__container">
                <div class="header__title">
                    Здраствуйте, Александра!
                </div>
            </div>
        </header>
        <div class="navigation-container-1">
            <nav class="navigation-1">
                <img src='#' alt="a picture" class="navigation-1__image">
                <button class="nav-button navigation-1__btn--attendance">Отметить посещаемость</button>
                <button class="nav-button navigation-1__btn--mark">Выставить оценки</button>
                <button class="nav-button navigation-1__btn--message">Личные сообщения</button>
                <button class="nav-button navigation-1__btn--task">Управление заданиями</button>
            </nav>
        </div>
        <main class="main">
            <div class="main__contaner">
                <table class="table">
                    <caption class="table__title">Расписаине на сегодня</caption>
                    <thead>
                        <tr>
                            <td>Группа, наименование предмета</td>
                            <td>№ каб.</td>
                            <td>Время</td>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td></td>
                            <td></td>
                            <td></td>
                        </tr>
                        <tr>
                            <td></td>
                            <td></td>
                            <td></td>
                        </tr>
                        <tr>
                            <td></td>
                            <td></td>
                            <td></td>
                        </tr>
                        <tr>
                            <td></td>
                            <td></td>
                            <td></td>
                        </tr>
                        <tr>
                            <td></td>
                            <td></td>
                            <td></td>
                        </tr>
                        <tr>
                            <td></td>
                            <td></td>
                            <td></td>
                        </tr>
                    </tbody>
                </table>
                <button class="main__button-go-to-attend-page">
                    Перейти к расписанию
                </button>
            </div>
        </main>
        <footer class="footer">
            <div class="navigetion-contaner-2">
                <nav class="navigation-2">
                    <button class="nav-button2 navigation__btn--profile">Profile</button>
                    <button class="nav-button2 navigation__btn--home">Home</button>
                    <button class="nav-button2 navigation__btn--faq">FAQ</button>
                </nav>
            </div>
        </footer>
    </div>
</body>

</template>



<script>
export default {
  name: 'Home'
  }
</script>
