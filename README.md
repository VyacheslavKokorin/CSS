# CSS
## Медиазапрос
Медиазапрос - это директива CSS, которая позволяет привязывать CSS-правила к определённым условиям среды.  
Брейкпоинт - это ориентир, который используется в медиазапросе для изменения дизайна. В примерах брейкпоинт равен 1000 пикселей.  
Применяется, когда ширина экрана от 1000 пикселей и больше:
```CSS
@media screen and (min-width: 1000px) {
	#wrapper {
		width: 800px;
	}
}
```
Применяется, когда ширина экрана до 1000 пикселей включительно:
```CSS
@media screen and (max-width: 1000px) {
	#wrapper {
		width: 800px;
	}
}
```
## Ширина/высота
Максимальная ширина равна 100% от ширины родителя.
```CSS
img {
	max-width: 100%;
}
```
# HTML
## Базовая структура HTML-страницы
```
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8" />
	<link href="style.css" rel="stylesheet" type="text/css" />
	<title>Web Page Structure</title>
</head>
<body>
</body>
</html>
```
## Тэги
### Ссылка
```HTML
<a href="google.com">Ссылка</a>
```
# Заметки
Мета-тег для блока head, которые приказывает браузеру отображать контент страницы по ширине экрана устройства.
```CCS
<meta name="viewport" content="width=device-width,initial-scale=1.0" />
```