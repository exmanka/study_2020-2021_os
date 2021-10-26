---
# Front matter
title: "Презентация по лабораторной работе №6"
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

Ознакомление с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.

# Выполнение лабораторной работы

  ![Задания из теории](image/Screenshot_1.png)

  ![Задания из теории](image/Screenshot_2.png)

  ![Задания из теории](image/Screenshot_3.png)

  ![Задания из теории](image/Screenshot_4.png)

  ![Задания из теории](image/Screenshot_5.png)

  ![Задания из теории](image/Screenshot_6.png)

  ![Копируем и называем файл](image/Screenshot_7.png)

  ![Создаем директорию и перемещаем файл](image/Screenshot_8.png)

  ![Переименовываем, создаем и перемещаем](image/Screenshot_9.png)

  ![Создаем каталог и перемещаем файлы](image/Screenshot_10.png)

  ![Создаем, перемещаем и называем каталог](image/Screenshot_11.png)

  ![Создаем файлы и изменяем их](image/Screenshot_12.png)

  ![Создаем файлы и изменяем их](image/Screenshot_13.png)

  ![Файла не существует](image/Screenshot_16.png)

  ![Используем файл /etc/passwd](image/Screenshot_17.png)

  ![Просматриваем содержимое файла](image/Screenshot_14.png)

  ![Просматриваем содержимое файла](image/Screenshot_15.png)

  ![Общий скриншот](image/Screenshot_18.png)


# Итог

Мы ознакомились с файловой системой Linux, её структурой, именами и содержанием каталогов. Приорели практические навыки по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.