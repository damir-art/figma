# Component Variants
Figma Component Variants.

Variants позволяет создавать один компонент с разными вариантами, раньше для этого требовалось создавать несколько компонентов.

Component Variants ускоряет работу и производительность труда. Отличный способ упростить Дизайн-Систему.

## Создание Component Variants
Рассмотрим Component Variants на примере прямоугольников:
- создаём три прямоугольника разного цвета
- каждый прямоугольник превращаем в мастер-компонент
- выделяем прямоугольники и объединяем их в Component Variants: `Variants > Combine as Variants`

Компонентам внутри Variants можно задавать свойства и значения.

- если сделать копию Component Variants, то получится не копия, а мастер-компонент
- если из Assets перетащить Component Variants, то перетащится один из вариантов и он будет копией компонента
- в свойствах копии можно выбирать один из вариантов

## Свойства Component Variants

## Свойства копии Component Variants

## Булево свойство в Component Variants
Например да/нет для кнопки, ставить иконку или нет. В значение свойств пишем `true` или `false`. При этом в свойствах появится переключатель, а не список.

## Новые варианты Component Variants
При добавлении новых вариантов, нужно выделить Component Variants > Выделить новые добавленные > Variants > Select conflicting variants > Добавить новое значение в свойство

Когда Component Variants уже готов и нужно добавить новые, то после их создания именуйте компоненты примерно так:

    Свойство=Значение, Свойство=Значение
    Color=Red, Radius=0

## Разное
- Прежде чем объединить мастер компоненты в Component Variants, желательно их правильно именовать
- Внутри Component Variants, можно выделить несколько компонентов и нажать на `+`, создадутся копии выделенных компонентов
- Наименование кнопок: `button/default`, `button/hover`, `button/focus`, `button/disabled`

Наименование подробнее:

    buttons/S/primary/normal
    buttons/M/secondary/disabled

    Size:  M/S
    Type:  primary/secondary
    State: default/hover/focus/disabled
