---
# Front matter
title: "Презентация по лабораторной работе №10"
author: "Ким Михаил Алексеевич"

# Generic otions
lang: ru-RU

# Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

# Pdf output format
toc: false # Table of contents
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Выполнение лабораторной работы

  ![Файл](image/Screenshot_11.png)

  ![Строка](image/Screenshot_12.png)

  ![Выделение области текста](image/Screenshot_13.png)

  ![Копирование и вставка](image/Screenshot_14.png)

  ![Вырезание](image/Screenshot_15.png)

  ![Отмена последнего действия](image/Screenshot_16.png)

  ![Перемещение курсора (начало строки)](image/Screenshot_17.png)

  ![Перемещение курсора (конец строки)](image/Screenshot_18.png)

  ![Перемещение курсора (начало буфера)](image/Screenshot_19.png)

  ![Перемещение курсора (начало буфера)](image/Screenshot_20.png)

  ![Перемещение курсора (конец буфера)](image/Screenshot_21.png)

  ![Cписок активных буферов](image/Screenshot_21.png)

  ![Перемещение курсора в соседнее окно](image/Screenshot_22.png)

  ![Выбор буфера](image/Screenshot_23.png)

  ![Переключение на выбранный буфер](image/Screenshot_24.png)

  ![Закртые окна](image/Screenshot_25.png)

  ![Переключение между буфферами](image/Screenshot_26.png)

  ![Деление фрейма](image/Screenshot_27.png)

  ![Открытие новых буферов](image/Screenshot_28.png)

  ![Режим поиска](image/Screenshot_29.png)

  ![Переключение между результатами поиска](image/Screenshot_30.png)

  ![Выход из режима поиска](image/Screenshot_31.png)

  ![Вход в режим замены](image/Screenshot_32.png)

  ![Вводим заменяемый текст](image/Screenshot_33.png)

  ![Вводим замену](image/Screenshot_34.png)

  ![Подтверждаем замену](image/Screenshot_35.png)

  ![Новый режим поиска](image/Screenshot_36.png)
  

# Итог

Мы углубили своё понимание операционной системой Linux. получили практические навыки работы с редактором emacs. Разобрали и опробывали его основные функции и возможности.