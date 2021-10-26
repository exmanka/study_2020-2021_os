---
# Front matter
title: "Лабораторная работа №8"
subtitle: "Командная оболочка Midnight Commander"
author: "Ким Михаил Алексеевич"

# Generic otions
lang: ru-RU
toc-title: "Содержание"

# Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

# Pdf output format
toc: true # Table of contents
toc_depth: 2
lof: false # List of figures
lot: false # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
### Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Misc options
indent: true
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Выполнение лабораторной работы

1. Изучаем информацию о mc, вызвав в командной строке man mc.(рис. 2.1)

    ```
    man mc
    ```

    ![man mc](image/Screenshot_1.png)

2. Запускаем из командной строки mc, изучаем его структуру и меню.(рис. 2.2)

    ```
    mc
    ```

    ![mc](image/Screenshot_2.png)

3. Выполняем несколько операций в mc, используя управляющие клавиши (операции с панелями; выделение/отмена выделения файлов, копирование/перемещение файлов, получение информации о размере и правах доступа на файлы и/или каталоги.) (рис. 2.3 - 2.7)

    ```
    Ctrl + u - переключить панель
    Ctrl + o - временно убрать отображение панели
    ```

    ![Ctrl + u - переключить панель](image/Screenshot_3.png)

    ![Ctrl + o - временно убрать отображение панели](image/Screenshot_4.png)

    ```
    Выделение/отмена выделения файлов:
    Ins
    Ctrl + T
    ```

    ![Выделение (Ins)](image/Screenshot_5.png)

    ![Отмена выделения (Ctrl + T)](image/Screenshot_6.png)

    ```
    F5 - копирование файлов
    F6 - перемещение файлов
    ```

    ![mc](image/Screenshot_7.png)

4. Выполняем основные команды меню левой (или правой) панели. Оцениваем степень подробности вывода информации о файлах: информации достаточно, для того чтобы получить понимание о свойствах файла, но не о его содержимом. (рис. 2.8 - 2.12)
   

    ![mc](image/Screenshot_8.png)

    ![mc](image/Screenshot_9.png)

    ![mc](image/Screenshot_10.png)

    ![mc](image/Screenshot_11.png)

    ![mc](image/Screenshot_12.png)

5. Создаем необходимый для работы файл. (рис. 2.13)

    ![mc](image/Screenshot_13.png)

6. Открываем его в редакторе mc, сохраняем изменения при помощи записи. (рис. 2.14-2.17)

    ![mc](image/Screenshot_15.png)

    ![mc](image/Screenshot_16.png)

    ```
    F7 - Создание нового каталогаа
    ```

    ![mc](image/Screenshot_17.png)

    ```
    F5 - Копирование файлов в созданный каталог
    ```

    ![mc](image/Screenshot_18.png)

7. С помощью соответствующих средств подменю Команда осуществляем: – поиск в файловой системе файла с заданными условиями (файла с расширением .cpp, содержащего строку main); – выбор и повторение одной из предыдущих команд; – переход в домашний каталог; – анализ файла меню и файла расширений.(рис. 2.18 - 2.26)

    ![mc](image/Screenshot_19.png)

    ![mc](image/Screenshot_20.png)

    ![mc](image/Screenshot_21.png)

    ![mc](image/Screenshot_22.png)

    ![mc](image/Screenshot_23.png)

    ![mc](image/Screenshot_25.png)

    ![mc](image/Screenshot_26.png)

    ![mc](image/Screenshot_27.png)

8. Вызываем подменю Настройки. осваиваем операции, определяющие структуру экрана mc.(рис. 2.27, 2.28)

    ![mc](image/Screenshot_28.png)

    ![mc](image/Screenshot_29.png)

9. Открываем созданный раннее файл text.txt и изменяем его.(рис. 2.28)

    ![mc](image/Screenshot_30.png)

    ![mc](image/Screenshot_31.png)

    ![mc](image/Screenshot_32.png)

    ![mc](image/Screenshot_33.png)

    ![mc](image/Screenshot_34.png)

    ![mc](image/Screenshot_35.png)

    ![mc](image/Screenshot_36.png)

    ![mc](image/Screenshot_37.png)

    ![mc](image/Screenshot_38.png)

    ![mc](image/Screenshot_39.png)

    ![mc](image/Screenshot_40.png)

    ![mc](image/Screenshot_41.png)

    ![mc](image/Screenshot_42.png)

    ![mc](image/Screenshot_43.png)

    ![mc](image/Screenshot_44.png)

    ![mc](image/Screenshot_45.png)

    ![Подсветка синтаксиса](image/Screenshot_46.png)

    ![M-Y](image/Screenshot_47.png)

# Выводы

Мы освоили основные возможности командной оболочки Midnight Commander. Приобрели навыки практической работы по просмотру каталогов и файлов и манипуляций с ними.

# Термины

* Файловая система (ФС) — архитектура хранения данных, которые могут находиться в разделах жесткого диска и ОП. [3]

* Каталог, он же директория, (от англисйкого Directory) – это объект в ФС (файловой системе), необходимый для того, чтобы упросить работу с файлами.

* Домашний каталог - каталог, предназначенный для хранения собственных данных пользователя Linux. Как правило, является текущим непосредственно после регистрации пользователя в системе.

* Команда - записанный по специальным правилам текст (возможно с аргументами), представляющий собой указание на выполнение какой-либо функций (или действий) в операционной системе.
* 
* Командная оболочка — интерфейс взаимодействия пользователя с операционной системой и программным обеспечением посредством команд.

* Midnight Commander (или mc) — псевдографическая командная оболочка для UNIX/Linux систем.

* Жесткая ссылка (hard link) является своего рода синонимом для существующего файла. Когда создаётся жесткая ссылка, создается дополнительный указатель на существующий файл, но не копия файла.

* Символическая ссылка (symbolic link) — это специальный файл, который является ссылкой на другой файл или каталог (их еще называют целевым файлом, целевым каталогом).

* Набор разрешений — это три блока прав доступа: права доступа для владельца файла, права доступа для группы, права доступа для всех остальных.

* Дерево каталогов — структура каталогов системы в виде "дерева".