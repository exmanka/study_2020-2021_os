---
# Front matter
title: "Презентация по лабораторной работе №8"
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

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Выполнение лабораторной работы

  ![man mc](image/Screenshot_1.png)

  ![mc](image/Screenshot_2.png)

  ![Ctrl + u - переключить панель](image/Screenshot_3.png)

  ![Ctrl + o - временно убрать отображение панели](image/Screenshot_4.png)

  ![Выделение (Ins)](image/Screenshot_5.png)

  ![Отмена выделения (Ctrl + T)](image/Screenshot_6.png)

  ![mc](image/Screenshot_7.png)

  ![mc](image/Screenshot_8.png)

  ![mc](image/Screenshot_9.png)

  ![mc](image/Screenshot_10.png)

  ![mc](image/Screenshot_11.png)

  ![mc](image/Screenshot_12.png)

  ![mc](image/Screenshot_13.png)

  ![mc](image/Screenshot_15.png)

  ![mc](image/Screenshot_16.png)

  ![mc](image/Screenshot_17.png)

  ![mc](image/Screenshot_18.png)

  ![mc](image/Screenshot_19.png)

  ![mc](image/Screenshot_20.png)

  ![mc](image/Screenshot_21.png)

  ![mc](image/Screenshot_22.png)

  ![mc](image/Screenshot_23.png)

  ![mc](image/Screenshot_25.png)

  ![mc](image/Screenshot_26.png)

  ![mc](image/Screenshot_27.png)

  ![mc](image/Screenshot_28.png)

  ![mc](image/Screenshot_29.png)

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


# Итог

Мы освоили основные возможности командной оболочки Midnight Commander. Приобрели навыки практической работы по просмотру каталогов и файлов и манипуляций с ними.