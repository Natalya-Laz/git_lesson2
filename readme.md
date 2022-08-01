## Инструкция по работе с маркдаун


## Выделение текста

Markdown воспринимает звёздочки «*» и символы подчёркивания «_» как признаки смыслового выделения текста:

Текст, окружённый одиночными «*» или «_», будет заключен в HTML-тэг <em>.
Текст, окружённый двойными «*» или «_», будет заключен в HTML-тэг <strong>.
Иными словами, текст, окруженный одинарными символами, выделяется курсивным шрифтом, а текст, окруженный двойными символами, выделяется полужирным шрифтом. Также, выделенный фрагмент может находиться в любой части слова. Текст, выделенный курсивом с использованием синтаксиса языка Markdown, выглядит следующим образом:

*Пример*  
Пример

Текст, выделенный полужирным шрифтом с использованием синтаксиса языка Markdown, выглядит следующим образом:

**Пример**
Пример

Текст, выделенный курсивным полужирным шрифтом с использованием синтаксиса языка Markdown выглядит следующим образом:

***Пример***




## Списки

Markdown поддерживает упорядоченные (нумерованные) и неупорядоченные (ненумерованные) списки. Для формирования неупорядоченный списков используются такие маркеры, как звездочки, плюсы и дефисы. Все перечисленные маркеры могут использоваться взаимозаменяемо. Для формирования упорядоченных списков в качестве маркеров используются числа с точкой. Важной особенностью в данном случае является то, что сами номера, с помощью которых формируется список, не важны, так как они не оказывают влияния на выходной HTML код. Как бы ни нумеровал пользователь список, на выходе он в любом случае будет иметь упорядоченный список, начинающийся с единицы (1, 2, 3…). 

Упорядоченные списки выглядят следующим образом:

1.	Проводник
2.	Полупроводник
3.	Диэлектрик
Неупорядоченные списки выглядят следующим образом:

* Проводник
* Полупроводник
* Диэлектрик

## Работа с изображениями

В Markdown существует 2 способа вставки изображений в документ:

a. С помощью непосредственного указания URL-адреса изображения. Синтаксис данной команды выглядит следующим образом:

![мученик науки](2,1.jpg)
или

![победа!!](2,2.jpg "Подсказка")
Иными словами, он состоит из следующих элементов:

* восклицательный знак;
* квадратные скобки, в которых указывается альтернативный изображению текст (он станет содержимым атрибута в элементе img);
* круглые скобки, содержащие URL-адрес или относительный путь изображения, а также (необязательно) всплывающую подсказку, заключённуе в двойные или одиночные кавычки.

## Ссылки

Markdown поддерживает два стиля оформления:

Гиперссылка с немедленным адресом (внутритекстовая);
Гиперссылка, похожая на сноске.
Подразумевается, что по URL-адресу не существует ссылки еще на текст. Он следует в квадратные скобки. Для создания внутритекстовой гиперссылки необходимо использовать круглые скобки сразу после закрывающей квадратной. Внутри них необходимо указать URL-адрес. В них же возможно утвердить название, Назначение в кавычки, которое будет назначено назначением, но этот пункт не является обязательным.

  [пример](http://example.com/ "Необязательная подсказка")
В результате на экране выводится следующее :

При создании сносной гиперссылки вместо целевого адреса используется вторая пара квадратных скобок, внутри которой помещается метка, идентификатор ссылки (id).

[пример][id]:
Также можно использовать пробел, чтобы отделять пары квадратных скобок:

[пример] [id]: 

## Цытаты 

Для цитирования в языке Markdown используется знак «больше» («>»). Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой абзаца. Также синтаксис Markdown позволяет создавать вложенные цитаты (цитаты внутри цитаты). Для их использования используются дополнительные уровни цитирования («>»). Цитаты в Markdown могут привести к обнаружению множественных элементов. Цитаты на языке Markdown

>Это пример цитаты,
>в которой перед каждой строкой
>ставится угловая скобка.

>Это пример цитаты,
в которой угловая скобка
ставится только перед началом нового параграфа.
>Второй параграф. 
Markdown поддерживает два стиля оформления:


