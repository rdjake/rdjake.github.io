# Neuromorphic Todo

Neuromorphic Todo - приложение для заметок, выполненное в необычном стиле «Неоморфизм».

[👉 Попробовать Neuromorphic Todo 👈](https://rdjake.github.io/Neuromorphic-Todo/)


![image](https://user-images.githubusercontent.com/60819667/200178619-af3538ae-2c0a-44f2-a7b5-7cacdc036599.png)

## Реализация

В приложении использован стек:
* Vite
* Vue3 (Composition API) 
* TypeScript 
* TailwindCSS

А также пакеты UUID и VueDraggable

## Детали
* UI авторский и адаптирован для использования на мобильных устройстах
<img src="https://your-image-url.type](https://user-images.githubusercontent.com/60819667/205435915-7b12d462-433f-4871-aafb-0bf87c1df7cd.png" width="600">


* Все кнопки имеют неоморфичное поведение (при нажатии «продавливаются»)
* Слева находится перечень списков:
  * Добавление нового списка происходит по нажатию на +.
  * Название нового списка вычисляется по шаблону "Новый список X". 
  * Изменить порядок списков можно перетащив нужный список мышкой (сопровождается анимацией). 
  * Удалние списка происходит по нажатию на крестик.
  * Нажатие на список, открыет его содержимое (спровождается анимацией). Повторное нажатие закрывает список.

* По центру находится содержимое текущего списка:
  * Добавить новый элемент можно по нажатию на +.
  * Новый элемент создается без текста, но с плейсхолдером "Новая заметка"
  * Изменить название списка можно по нажатию на него.
  * Закрыть список можно по нажатию на крестик (сопровождается анимацией).
  * Отметить элемент списка, как выполненный, можно по нажатию на пустой кружок.
  * У выполенных элементов кружок «продавливается», а текст затухает и зачеркивается.
  * Редактировать текст элемента списка можно по нажатию в любой области этого элемента.
  * Во время редактирования элемент выделяется цветом.
  * Элементы списка можно перетаскивать с помощью кнопки с 3 полосками (сопровождается анимацией).
  * Удалять элементы можно по нажатию на крестик.
  
* Для каждого списка и элемента списка создается свой ID из UUID.
* При первом запуске генерируются приложения генерируются примеры списков (Дела, Покупки).
* При последующих запусках приложение достает пользовательские списки из cookie браузера.
* Для приложения выбран шрифт Nunito от Google Fonts. 
  
  
