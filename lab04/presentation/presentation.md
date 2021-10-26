---
# Front matter
title: "Презентация по лабораторной работе №4"
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

Ознакомиться с операционной системой Linux, получить практические навыки работы с консолью и некоторыми графическими менеджерами рабочих столов операционной
системы.

# Выполнение лабораторной работы

![Виртуальные терминалы](image/Screenshot_1.png)

![Виртуальные терминалы](image/Screenshot_2.png)

![Регистрация в виртуальном терминале](image/Screenshot_3.png)

![Завершение сеанса](image/Screenshot_4.png)

![Переключение на графический интерфейс](image/Screenshot_5.png)

![Браузер Mint Cinnamon 20.2](image/Screenshot_6.png)

![Текстовый редактор Mint Cinnamon 20.2](image/Screenshot_7.png)

![Текстовый процессор Mint Cinnamon 20.2](image/Screenshot_8.png)

![Эмулятор консоли Mint Cinnamon 20.2](image/Screenshot_9.png)

![Браузер CentOS 7](image/Screenshot_10.png)

![Текстовый редактор CentOS 7](image/Screenshot_11.png)

![Текстовый процессор CentOS 7 (можно скачать)](image/Screenshot_12.png)

![Эмулятор консоли CentOS 7](image/Screenshot_13.png)

# Итог

Мы познакомились с операционной системой Linux, получили практические навыки работы с текстовой консолью и некоторыми графическими менеджерами рабочих столов операционной системы, в частности изучили их работу и нашли отличия.