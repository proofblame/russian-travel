# Проект 3: Путешествие по России

**Table of Contents**

[TOCM]

[TOC]

### About
------------
Данный проект является третьей проектной работой курса Адаптивная вёрстка и работа с макетом,  а также последней работой по изучению верстки.

### Installation and Usage
------------
Для ознакомления с результатами самостоятельной работы необходимо пройти по данной [ссылке](https://proofblame.github.io/russian-travel/ "Путешествие по России").

### Features
------------
- HTML5;
- CSS3;
- Flexbox;
- Grid;
- Responsive layout;
- Adaptive layout;
- Relative size;
- Local fonts used;
- BEM technology;
- File structure - NESTED.

### Breaking points
------------
Для облегчения поиска, ниже представлен список точек разрыва в которых использованы блоки и элементы.

    @media screen and (max-width: 1280px) {
        .header
        .photo-grid
        .cover
        .footer
    }

    @media screen and (max-width: 1080px) {
        .lead
            .lead__subtitle
        .intro
        .places
        .place
    }

    @media screen and (max-width: 1024px) {
        .photo-grid 
    }
    
    @media screen and (max-width: 928px) {
        .lead
            .lead__image
            .lead__caption
        .intro
        .photo-grid
        .places
        .place
            .place__title
            .place__paragraph
        .cover
        .footer
    }
    
    @media screen and (max-width: 755px) {
        .place__website
    }
    
    @media screen and (max-width: 736px) {
        .header
            .header__lang-link 
        .lead
            .lead__title
            .lead__subtitle
        .intro
            .intro__title
            .intro__text
            .intro__list
        .photo-grid
        .places
        .place
        .cover
            .cover__title
            .cover__subtitle
        .footer
        .footer__links
        .footer__copyright
    }
    
    @media screen and (max-width: 611px) {
        .place__title
    }

### Contributing
------------
Критика и указания на допущенные ошибки приветствуются!

### Plans
------------
Дописать все вендорные префиксы;
Задизайнить форму, через которую пользователи смогут отправить комментарий.
###  Authors
------------
Marokko Timur - студент Яндекс Практикума.

### Gratitude
------------
- Семье и близким, поддерживающим в период обучения и бессонных ночей.
-  Яндекс Практикуму, предоставившему возможность осуществить свою мечту и работать в удовольствие.

### License
------------
[MIT License](https://choosealicense.com/licenses/mit/ "MIT License")