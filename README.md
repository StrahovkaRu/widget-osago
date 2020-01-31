# Strahovka.ru виджет ОСАГО

## Использование для партнеров

Вставьте следующий код в вашу html страницу:

#### Мобильная версия
```html
<str-widget-osago width="340" /> 
<script async src="https://github.com/StrahovkaRu/widget-osago/releases/download/0.1.0/str-widget-osago.js"></script>
```
#### Десктопная версия
```html
<str-widget-osago width="1170" /> 
<script async src="https://github.com/StrahovkaRu/widget-osago/releases/download/0.1.0/str-widget-osago.js"></script>
```

Поместите тег `<str-widget-osago />` в тег `<body>` вашего сайта, в том месте где вы хотите чтобы показывался виджет

Поместите тег `<script>` внизу `<body>` с другими скриптами 

**Пояснения**

* Атрибут `width` в теге `<str-widget-osago />` контролирует ширину виджета 
* Атрибут `async` в теге `<script>` делает загрузку асинхронной, т.е. подключение виджета произойдет после первичной отрисовки страницы
