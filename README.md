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