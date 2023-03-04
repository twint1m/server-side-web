# Лабораторная работа №1

## 1. С помощью BEM описать человеческое тело

    голова
        голова__глаза--зеленые
        голова__волосы--кудрявые
        голова__нос
    тело
        тело__спина
        тело__пресс
        тело__шея
    рука
        рука__локоть
        рука__кисть
        рука__пальцы--длинные


## 2. Подготовить создание 4 различных блоков из макета в нотации Emmet

### a. Блок Header

![Блок Header](/img/header.png)

Emmet нотация:

`header.header>(a.header__logo>img.header__svg)+(nav.nav>ul.header__contact>li.header__items*4>a.header__links)+ul.header__info>li.header__item*4>a.header__link`

Результат:

`   <header class="header">
            <a href="" class="header__logo">
                <img src="" alt="" class="header__svg">
            </a>
        <nav class="nav">
            <ul class="header__contact">
                <li class="header__items">
                    <a href="" class="header__links"></a>
                </li>
                <li class="header__items">
                    <a href="" class="header__links"></a>
                </li>
                <li class="header__items">
                    <a href="" class="header__links"></a>
                </li>
                <li class="header__items">
                    <a href="" class="header__links"></a>
                </li>
            </ul>
        </nav>
        <ul class="header__info"
            <li class="header__item">
                <a href="" class="header__link"></a>
            </li>
            <li class="header__item">
                <a href="" class="header__link"></a>
            </li>
            <li class="header__item">
                <a href="" class="header__link"></a>
            </li>
        </ul>
    </header>`


### b. Блок Form

![Блок Header](/img/form.png)

Emmet нотация:

`form.form>h2.form__legend+(label.form__label+input.form__input)*2+button.form__button`

Результат:

`   <form action="" class="form">
        <h2 class="form__legend"></h2>
        <label for="" class="form__label"></label>
        <input type="text" class="form__input">
        <label for="" class="form__label"></label>
        <input type="text" class="form__input">
        <button class="form__button"></button>
    </form>`


### c. Блок Card

![Блок Header](/img/card.png)

Emmet нотация:

`.card>span.card__sale+h2.card__title+(.card__price>p.card__cost+span.card__line+p.card__cost)+ul.card__desc>li.card__item*3`

Результат:

`   <div class="card">
        <span class="card__sale"></span>
        <h2 class="card__title"></h2>
        <div class="card__price">
            <p class="card__cost"></p>
            <span class="card__line"></span>
            <p class="card__cost"></p>
        </div>
        <ul class="card__desc">
            <li class="card__item"></li>
            <li class="card__item"></li>
            <li class="card__item"></li>
        </ul>
    </div>`



### c. Блок Advantage

![Блок Header](/img/advantage.png)

Emmet нотация:

`.advantage>img.advantage__icon+p.advantage__text`

Результат:

   `<div class="advantage">
        <img src="" alt="" class="advantage__icon">
        <p class="advantage__text"></p>
    </div>`











