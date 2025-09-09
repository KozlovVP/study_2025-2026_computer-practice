---
## Front matter
title: "Отчёт по лабораторной работе №1"
subtitle: "Julia. Установка и настройка. Основные принципы."
author: "Козлов Всеволод Павлович НФИбд-02-22"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: Arial
romanfont: Arial
sansfont: Arial
monofont: Arial
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
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Основная цель работы — подготовить рабочее пространство и инструментарий для
работы с языком программирования Julia, на простейших примерах познакомиться
с основами синтаксиса Julia.

# Задание

1. Установите под свою операционную систему Julia, Jupyter.
2. Используя Jupyter Lab, повторите примеры.
3. Выполните задания для самостоятельной работы.

# Выполнение лабораторной работы

Установил Chocolatey (рис. [-@fig:001])

![Установка Chocolatey](image/1.png){ #fig:001 width=70% }

Установил Far (рис. [-@fig:002])

![Установка Far](image/2.png){ #fig:002 width=70% }

Установил Notepad++ (рис. [-@fig:003])

![Установка Notepad++](image/3.png){ #fig:003 width=70% }

Установил Julia (рис. [-@fig:004])

![УСтановка Julia](image/4.png){ #fig:004 width=70% }

Установил доп пакет IJulia (рис. [-@fig:005])

![Установка IJulia](image/5.png){ #fig:005 width=70% }

Установил Anaconda 3 (рис. [-@fig:006])

![Установка Anaconda3](image/6.png){ #fig:006 width=70% }

Документация по println и ее использование (рис. [-@fig:007])

![Документация по println и ее использование](image/7.png){ #fig:007 width=70% }

Документация по readline и ее использование (рис. [-@fig:008])

![Документация по readline и ее использование](image/8.png){ #fig:008 width=70% }

Документация по readlines и ее использование (рис. [-@fig:009])

![Документация по readlines и ее использование](image/9.png){ #fig:009 width=70% }

Документация по readlm и ее использование (рис. [-@fig:010])

![Документация по readlm и ее использование](image/10.png){ #fig:010 width=70% }

Документация по show и ее использование (рис. [-@fig:011])

![Документация по show и ее использование](image/11.png){ #fig:011 width=70% }

Документация по write и ее использование (рис. [-@fig:012])

![Документация по write и ее использование](image/12.png){ #fig:012 width=70% }

Документация по parse и ее использование (рис. [-@fig:013])

![Документация по parse и ее использование](image/13.png){ #fig:013 width=70% }

Арифметика, степени и корни в Julia (рис. [-@fig:014])

![Арифметика, степени и корни в Julia](image/14.png){ #fig:014 width=70% }

Сравнения и логика в Julia (рис. [-@fig:015])

![Сравнения и логика в Julia](image/15.png){ #fig:015 width=70% }

Операции с разными типами данных в Julia (рис. [-@fig:016])

![Операции с разными типами данных в Julia](image/16.png){ #fig:016 width=70% }

Операции с матрицами в Julia (рис. [-@fig:017])

![Операции с матрицами в Julia](image/17.png){ #fig:017 width=70% }

Операции с матрицами в Julia (рис. [-@fig:018])

![Операции с матрицами в Julia](image/18.png){ #fig:018 width=70% }

# Выводы

Подготовил рабочее пространство и инструментарий для
работы с языком программирования Julia, на простейших примерах познакомился
с основами синтаксиса Julia.

# Список литературы
1. Julia 1.5 Documentation. — 2020. — URL: https://docs.julialang.org/en/v1/.
2. Klok H.,Nazarathy Y. Statistics with Julia: Fundamentals for Data Science,Machine Learning
and Artificial Intelligence. — 2020. — URL: https://statisticswithjulia.org/.
3. Ökten G. First Semester in Numerical Analysis with Julia. — Florida State University, 2019. —
DOI: 10.33009/jul.
4. Антонюк В. А. Язык Julia как инструмент исследователя. — М. : Физический факультет
МГУ им. М. В. Ломоносова, 2019.
5. Шиндин А. В. Язык программирования математических вычислений Julia. Базовое
руководство. — Нижний Новгород : Нижегородский госуниверситет, 2016.