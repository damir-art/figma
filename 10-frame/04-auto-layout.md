# Auto Layout
Создадим список: иконка + текст
- выделяем иконку и текст
- жмем в панели свойств `Auto Layout`
- оба элемента окажутся внутри контейнера
- Центрируем элементы:
    - выделяем контейнер `Auto Layout`
    - в панели свойств жмём по `Alignment and Padding`
    - выбираем лево и центр
- Добавляем элементы списка
    - дублируем фрейм-контейнер `Auto Layout`
    - оборачиваем копии в еще один контейнер `Auto Layout`

## Свойства фрейм-контейнера `Auto Layout`
## Auto Layout
Отступ между элементами, внутренний отступ `padding`, выравнивание элементов внутри фрейма (не работает если отступы со всех сторон одинаковы), также здесь можно настраивать `padding` отдельно для каждой стороны.

## Constraints and Resizing
Стандартно для фрейма `left/top` и `Hug contents`. Для дочерних фреймов `Hug contents`.

## Разное
- чтобы добавить один элемент, например текст в `Auto Layout`, сначала его нужно добавить в группу
- Для большей гибкости, `Auto Layout`ы можно вкладывать в другие `Auto Layout`ы