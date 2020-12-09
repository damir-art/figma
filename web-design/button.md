## Кнопка
Руководство по Figma: https://figma.su

Создание кнопок

* Текст кнопок делать капслоком.
* Капслок делать через Figma, а не клавиатуру. 
* Межбуквенное расстояние (кернинг) 3/5/10%

## Как сделать равные паддинги по сторонам?
Стандартный способ через Auto Layout:
* Пишем текст
* Line Height - 100% (равный размеру шрифта)
* Правая кнопкая мыши по тексту
* Выбираем Add Auto Layout `Shift + A`
* Текст добавится во фрейм
* Во фрейме в свойствах Auto Layout задаём паддинги
* Добавляем фрейму фон или обводку (размер можно числами с плавающей точкой, подстраивая под толщину шрифта)

Другой способ:
* Выделяем текст кнопки
* Зажимаем `Alt`
* Отводим курсор мыши от текста к кнопке
* Смотрим текущие расстояния по сторонам
* Увеличиваем/уменьшаем размеры ширины/высоты