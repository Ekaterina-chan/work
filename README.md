[![Android Studio version](https://img.shields.io/endpoint?url=https%3A%2F%2Fsicampus.ru%2Fgitea%2Fcore%2Fdocs%2Fraw%2Fbranch%2Fmain%2Fandroid-studio-label.json)](https://sicampus.ru/gitea/core/docs/src/branch/main/how-upload-project.md)

# Практическая работа. Подарочек

В данном практическом задании предлагается дописать существующий проект Android приложения, а именно дополнить разметку.

1. В разметке приложения в любой ориентации должны присутствовать элементы, указанные в табл. 1. У кнопки должен быть установлен строковый ресурс из табл. 2
2. В портретной ориентации: в *ImageView* должен быть установлен ресурс `@drawable/orange`, кнопка должна находиться строго под картинкой.
3. В ландшафтной ориентации: вместо оранжевой коробочки в *ImageView* должна отображаться коробочка синего цвета `@drawable/blue`, картинка должна быть расположена слева от кнопки.

| № | View type | id |
| :-: | ------- | -- |
| 0 | *Button* | `test_button` |
| 1 | *ImageView* | `box_image` |

*Таблица 1. Элементы пользовательского интерфейса*

| № | Ресурс | Допустимое значение |
| :-: | ------- | -- |
| 0   | `@string/main_text_button` | Test Button |

*Таблица 2. strings.xml*