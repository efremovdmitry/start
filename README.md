# start
**Компиляция** `sass` командой `sass --watch source/scss/style.scss:dist/style.css`

### JavaScript код  
`npm init -y`  
`npm install laravel-mix --save-dev`  
**Запустить** `npx mix watch`  

> webpack.mix.js  
```
let mix = require('laravel-mix')
mix.js('source/javascript/main.js', 'dist')
```


# Libs:

## @ciar4n/izmir
Измир - это мини-библиотека CSS, позволяющая быстро создавать красивые элементы навеса изображения. Упакованный множеством классов стиля и пользовательских свойств, Izmir обеспечивает полный контроль и почти безграничные возможности. Просто загрузите библиотеку CSS в свой проект, добавьте разметку элемента в сочетании с классами стилей по вашему выбору, чтобы создать идеальный эффект навеса изображения.
```
<figure class="c4-izmir">
    <img src="https://source.unsplash.com/FaPxZ88yZrw/400x300" alt="Sample Image">
    <figcaption>
    <h3>
        Some sample text
    </h3>
    </div>
</figure>
```

## Swiper
