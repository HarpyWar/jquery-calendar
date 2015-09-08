
jquery-calendar
===============

Форк [oneyoung/jquery-calendar](https://github.com/oneyoung/jquery-calendar) адаптированный под русский язык.

- исправлен формат даты дд.мм.гггг
- добавлены месяцы и недели на русском
- исправлен начальный день недели с воскресенья на понедельник

![](http://i.imgur.com/h5gs5Bu.png)


## Демо

See [this page](http://oneyoung.im/jquery-calendar/demo).

## Установка

+ jQuery
```html
  <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
```

+ Javascript + CSS
```html
  <script type="text/javascript" src="js/calendar.js"></script>
  <link rel="stylesheet" href="css/calendar.css" />
```

### Date Picker

Для текстового поля можно установить дату по-умолчанию в формате `DD.MM.YYYY`:
```html
<input class="date-picker" type="text" value="2013-8-1" />
```

Два варианта использования

+ css класс: `date-picker`
```html
<input class="date-picker" type="text" />
```

+ вызов через js `$.datePicker()`
```html
<script>
$(window).load(function() {
  $(".your-picker").datePicker();
}
</script>
<input class="your-picker" type="text" />
```
