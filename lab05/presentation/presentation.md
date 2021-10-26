---
# Front matter
title: "Презентация по лабораторной работе №5"
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

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

# Выполнение лабораторной работы

  ![Полное имя домашнего каталога](image/Screenshot_1.png)

  ![ls](image/Screenshot_2.png)

  ![ls -a](image/Screenshot_3.png)

  ![ls -F](image/Screenshot_4.png)

  ![ls -aF](image/Screenshot_5.png)

  ![ls -l](image/Screenshot_6.png)

  ![ls -alF](image/Screenshot_7.png)

  ![Подкаталог cron существует](image/Screenshot_8.png)

  ![Вывод домашнего каталога](image/Screenshot_9.png)

  ![Создание каталогов. Команду mkdir newdir закрывает изображение с веб-камеры](image/Screenshot_10.png)

  ![Создание трех каталогов (изначально были неправильно созданы с запятой)](image/Screenshot_11.png)

  ![Удаление каталога](image/Screenshot_12.png)

  ![ls -R](image/Screenshot_13.png)

  ![ls -R](image/Screenshot_14.png)

  ![ls -u -lt](image/Screenshot_15.png)

  ![man man](image/Screenshot_16.png)

  ![man cd](image/Screenshot_17.png)

  ![man pwd](image/Screenshot_18.png)

  ![man mkdir](image/Screenshot_19.png)

  ![man rmdir](image/Screenshot_20.png)

  ![man rm](image/Screenshot_21.png)

  ![Часть history](image/Screenshot_22.png)

  ![!32:s/new/old](image/Screenshot_23.png)

  ![!34:s/new/old](image/Screenshot_24.png)

  ![!48:s/new/old](image/Screenshot_25.png)

# Итог

Приобретены практические навыкы взаимодействия пользователя с системой посредством командной строки. Изучены новые команды и их опции. улучшено понимание работы Linux.