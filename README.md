# Описание:

Программа представляет собой воспроизводитель визуальных новелл в консоль. Файл новеллы представляет из себя текстовый формат, который легко редактировать.

Язык программирования: С++.

# Execute:

[[Give me a story and I show you magic.exe]]
![[VNR.exe]]
# Инструкция по использованию:

 `s<time>`- команда настройки задержки печати букв (в миллисекундах):

```jsx
`s100` - задержка 100 миллисекунд
```

`d<time>` - команда задержки печати (в миллисекундах):

```jsx
`d100` - задержка 100 миллисекунд
```

`c<color-index>` - настройка цвета шрифта с индексом 15
`w...` - настройка экрана(с параметрами)/ожидание клавиши 
- `...n<win-name>` - настройка названия окна на 'VNR'
- `...x<x-coord>` - настройка положения окна на 100 пикселей по X от верхнего левого угла экрана   
- `...y<y-coord>` - настройка положения окна на 100 пикселей по Y от верхнего левого угла экрана
`m<song-name>` - воспроизведение музыки(с параметрами)/воспроизвести один раз   
- `...s` - остановить музыку
- `...l<song-name>`- воспроизводить циклично 

 перевод строки 

 стереть с экрана

По умолчанию все параметры сброшены к нулю.

P.S.: на windows 7 все функции работали, в windows 10 нет настройки экрана

# Пример файлов новеллы:

```jsx
`s100`Hello,`d1000``c10` World`mlRecord.wav`
```

# Доработки на будущее:

- настройка экрана
- настройка цветов в разных индексах цвета
