---
title: Use export to Reuse a Code Block
localeTitle: Использовать экспорт для повторного использования блока кода
---
## Использовать экспорт для повторного использования блока кода

Мы узнали, как импортировать материал из другого файла. Но есть улов. Вы можете импортировать только файлы, **экспортированные** из этого другого файла.

Ваша задача - экспортировать `foo` и `bar` .

## Подсказка 1:

Просто добавьте экспорт перед ними!

## Оповещение о спойлере - решение впереди!

## Решение

```javascript
"use strict"; 
 export const foo = "bar"; 
 export const bar = "foo"; 

```