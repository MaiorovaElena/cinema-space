# КиноКосмос

***Узнай о фильмах всё и поделись своим мнением!***


На нашем сайте вы можете найти информацию о фильмах, рецензии, отзывы пользователей и сами оставить отзыв.

###  Описание проекта
Сайт представляет собой информационный ресурс о фильмах с возможностью авторизации пользователя и сохранением его выбора фильмов в базе данных. 
В проекте была использована база данных https://console.firebase.google.com/. 
Для отображении информации о фильмах использовался API https://kinopoiskapiunofficial.tech/

#### Header:
Header представлен на всех страницах проекта. Включает в себя:
- Лого, при клике на который происходит переход на главную страницу;
- Ссылку на страницу каталога
- Поиск по ключевым словам. При вводе слова отображается список фильмов через который можно перейти на страницу выбранного фильма
- Атрибуты личного кабинета:
    - Кнопка войти, если пользователь не авторизован. При нажатии, открывается модальное окно входа в личный кабинет, через которое можно зайти на форму регистрации, если пользователь не зарегистрирован. Реализована возможность восстановления пароля;
    - Приветствие авторизованного пользователя, при нажатии на аватарку происходит переход в личный кабинет;
    - Кнопка выхода из личного кабинета. При нажатии на кнопку выхода, в случае, если пользователь находится в личном кабинете, происходит переход на главную страницу.
При уменьшении ширины экрана до 599 пикселей, header отображается в виде бургер-меню, в котором содержатся все элементы header, кроме лого

#### Главная страница:
На главной странице предсталены:
- заголовок, слоган, текст;
- карточки фильмов из топа популярных фильмов, которые отображаются в рандомном порядке. При нажатии на название фильма, осуществляется переход на страницу фильма;
- цитаты, которые генерируются нейронной сетью.

#### Личный кабинет:
На страницу личного кабинета может войти только авторизованный пользователь. 
В ней содержатся фильмы, которые были добавлены пользователем в избранное. Пользователь может удалить фильмы из избранного.
Есть возможность создания пользователем своего списка. Нереализованный еще  функционал состоял в том, чтобы у пользователя была возможность добавлять фильмы в свои созданные списки.

#### Страница фильма:
Страница фильма содержит:
- Подробное описание фильма с основными актерами, которые в нем учавствовали;
- Сезоны сериалов и их описание;
- Возможность добавить фильм в избранное. Если на эту страницу заходит авторизованный пользователь, и фильм у него в избранном, то это видно по окраске иконки. Есть возможность при повторном нажатии на иконку, удалить фильм из избранного пользователя. В случае если неавторизованный пользователь попытается добавить фильм в избранное, то откроемся модальное окно для авторизации пользователя;
- Отзывы пользователей кинопоиска;
- Отзывы пользователей, авторизованные на нашем сайте;
-Возможность авторизованному пользователю добавить отзыв. При попытке добавления отзыва неавторизованному пользователю во вкладке пользователю будет предложено авторизоваться, при нажатии на кнопку, откроется модальное окно авторизации.

#### Каталог:
В каталоге можно с помощью указанных в нем фильтров наайти список фильмов. Реализованы фильтры по жанру, стране и категории (фильм, сериал, Тв шоу).
Список фильмов отсортирован по рейтингу от большего к меньшему.
Всего API, который был использован в проекте позволяет отобразить 100 фильмов, по 20 фильмов на странице. Пагинация реализована с помощью скроллинга, где при достижении пользователем конца страницы, подгружается следующая.
Так же реализована возможность добавить фильм в избранное. Если на эту страницу заходит авторизованный пользователь, и фильм у него в избранном, то это видно по окраске иконки. Есть возможность при повторном нажатии на иконку, удалить фильм из избранного пользователя. В случае если неавторизованный пользователь попытается добавить фильм в избранное, то откроемся модальное окно для авторизации пользователя.
При нажатии на название фильма, осуществляется переход на страницу фильма



### Технологии и инструменты

<div align="center">
    <img src="https://img.shields.io/badge/javascript-323330?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript"/>
    <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
    <img src="https://img.shields.io/badge/sass-CF649A?style=for-the-badge&logo=Sass&logoColor=white" alt="SASS"/>
    <img src="https://img.shields.io/badge/git-%23F05033?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
    <img src="https://img.shields.io/badge/github-121011?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
    <img src="https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white" alt="Firebase"/>
    <img src="https://img.shields.io/badge/vite-646CFF.svg?style=for-the-badge&logo=Vite&logoColor=white" alt="Vite"/>
    <a title="Kinopoisk Unofficial API" href="https://kinopoiskapiunofficial.tech/">
        <img src="https://img.shields.io/badge/api-1B1818?style=for-the-badge"/>
    </a>
</div>


### Команда проекта

<div align="center">
    <a href="https://github.com/MarinaIatsuk/F64_JS2_Project/graphs/contributors">
        <img src="https://contrib.rocks/image?repo=MarinaIatsuk/F64_JS2_Project" width="520"/>
    </a>
</div>




<p align="center">
  <samp>
    <a href="https://github.com/MarinaIatsuk">Marina</a> •
    <a href="https://github.com/fukuniji">Nat</a> •
    <a href="https://github.com/AlinaSun0201">Alina</a> •
    <a href="https://github.com/Chuchundra009">Helen</a> •
    <a href="https://github.com/Yanastya89">Anastasiia</a> •
    <a href="https://github.com/slastinatalia">Nataliia</a> •
    <a href="https://github.com/NikaAzizova">Nika</a>
  </samp>
</p>
