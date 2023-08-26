# Создание справки по системе контроля версий GIT


## Как начать?
**Чтобы начать работать с системой контроля версий Git, необходимо выполнить следующую команду:**

```cs
git init
```

## Как добавить файл в отслеживание

**Чтобы добавить файл в отслеживание, используйте команду:**

```
git add namefile
```

или

```
git add .
```



# Создания руководства по языку раметки MarkDawn


## Создание заголовков




## Добавление изображений

Чтобы добавить изображения, можно воспользоваться следующими конструкциями:

Картинка без `alt` текста

![](https://www.advantour.com/img/kazakhstan/images/nature.jpg)

Картинка с альтом и тайтлом:

![Alt text](https://www.advantour.com/img/kazakhstan/images/nature.jpg "Можно задать title")

Запомнить просто: синтаксис как у ссылок, только перед открывающей квадратной скобкой ставится восклицательный знак.

Картинки «сноски»:

![Картинка](https://www.advantour.com/img/kazakhstan/images/nature.jpg)
![Картинка][image2]
![Картинка][image3]

[image1]: //placehold.it/250x100
[image2]: //placehold.it/200x100
[image3]: //placehold.it/150x100

Картинки-ссылки:

[![Alt text](https://www.advantour.com/img/kazakhstan/images/nature.jpg)](https://www.youtube.com/watch?v=1s6oJSVmr4c)





## Добавление исходного кода

В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть более удобный способ: ставим по три апострофа (на букве Ё) до и после кода. Также можно указать язык исходного кода.

```pyton
@route("/")
def start():
    return render("index.html")
```


## Добавление таблиц

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть.

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Для красоты можно и по бокам линии нарисовать:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

Можно управлять выравниванием столбцов при помощи двоеточия.

| Left-Aligned  | Center Aligned  | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is      | some wordy text |     **$1600** |
| col 2 is      | centered        |         $12   |
| zebra stripes | are neat        |        ~~$1~~ |

Внутри таблиц можно использовать ссылки, наклонный, жирный или зачеркнутый текст.

Для всего остального есть обычный HTML.

