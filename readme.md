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

`header.header>(section.header__logo>img.header__svg)+(ul.header__contact>li.header__item-$*4)+ul.header__info>a.header__links-$*3`

Результат:

`   <header class="header">
        <section class="header__logo"><img src="" alt="" class="header__svg"></section>
        <ul class="header__contact">
            <li class="header__item-1"></li>
            <li class="header__item-2"></li>
            <li class="header__item-3"></li>
            <li class="header__item-4"></li>
        </ul>
        <ul class="header__info"><a href="" class="header__links-1"></a><a href="" class="header__links-2"></a><a href="" class="header__links-3"></a></ul>
    </header>`


### b. Блок Form

![Блок Header](/img/form.png)

Emmet нотация:

`form.form>label.form__label+input.form__input+button.form__button`

Результат:

`   <form class="form">
        <label class="form__label" for="input-email">Email</label>
        <input class="form__input" type="email" id="input-email" name="email">
        <button class="form__button">Submit</button>
    </form>`


### c. Блок Card

![Блок Header](/img/card.png)

Emmet нотация:

`.card>span.card__sale+h2.card__title+(.card__price>p.card__cost+span.line+p.card__cost)+ul.card__desc>li.card__item*3`

Результат:

`   <div class="card">
        <span class="card__sale"></span>
        <h2 class="card__title"></h2>
        <div class="card__price">
            <p class="card__cost"></p>
            <span class="line"></span>
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











