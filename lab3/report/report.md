---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Управляющие структуры"
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

Основная цель работы — освоить применение циклов функций и сторонних для Julia
пакетов для решения задач линейной алгебры и работы с матрицами.

# Задание

1. Используя Jupyter Lab, повторите примеры из отчета.
2. Выполните задания для самостоятельной работы.

# Выполнение лабораторной работы

Цикл while (рис. [-@fig:001])

![Цикл while](image/1.png){ #fig:001 width=70% }

Цикл for (рис. [-@fig:002])

![Цикл for](image/2.png){ #fig:002 width=70% }

Массивы (рис. [-@fig:003])

![Массивы](image/3.png){ #fig:003 width=70% }

Массивы (рис. [-@fig:004])

![Массивы](image/4.png){ #fig:004 width=70% }

Условное выражение (рис. [-@fig:005])

![Условное выражение](image/5.png){ #fig:005 width=70% }

Условное выражение (рис. [-@fig:006])

![Условное выражение](image/6.png){ #fig:006 width=70% }

Функции примеры (рис. [-@fig:007])

![Функции примеры](image/7.png){ #fig:007 width=70% }

Функции примеры (рис. [-@fig:008])

![Функции примеры](image/8.png){ #fig:008 width=70% }

Функции примеры (рис. [-@fig:009])

![Функции примеры](image/9.png){ #fig:009 width=70% }

Функции примеры (рис. [-@fig:010])

![Функции примеры](image/10.png){ #fig:010 width=70% }

Функции примеры (рис. [-@fig:011])

![Функции примеры](image/11.png){ #fig:011 width=70% }

Сторонние библиотеки (рис. [-@fig:012])

![Сторонние библиотеки](image/12.png){ #fig:012 width=70% }

Самостоятельная работа. Задание 1 (рис. [-@fig:013])

![Самостоятельная работа. Задание 1](image/13.png){ #fig:013 width=70% }

Самостоятельная работа. Задание 1 (рис. [-@fig:014])

![Самостоятельная работа. Задание 1](image/14.png){ #fig:014 width=70% }

Самостоятельная работа. Задание 2 (рис. [-@fig:015])

![Самостоятельная работа. Задание 2](image/15.png){ #fig:015 width=70% }

Самостоятельная работа. Задание 3-4 (рис. [-@fig:016])

![Самостоятельная работа. Задание 3-4](image/16.png){ #fig:016 width=70% }

Самостоятельная работа. Задание 5 (рис. [-@fig:017])

![Самостоятельная работа. Задание 5](image/17.png){ #fig:017 width=70% }

Самостоятельная работа. Задание 6 (рис. [-@fig:018])

![Самостоятельная работа. Задание 6](image/18.png){ #fig:018 width=70% }

Самостоятельная работа. Задание 7 (рис. [-@fig:019])

![Самостоятельная работа. Задание 7](image/19.png){ #fig:019 width=70% }

Самостоятельная работа. Задание 7 (рис. [-@fig:020])

![Самостоятельная работа. Задание 7](image/20.png){ #fig:020 width=70% }

Самостоятельная работа. Задание 7 (рис. [-@fig:021])

![Самостоятельная работа. Задание 7](image/21.png){ #fig:021 width=70% }

Самостоятельная работа. Задание 8 (рис. [-@fig:022])

![Самостоятельная работа. Задание 8](image/22.png){ #fig:022 width=70% }

Самостоятельная работа. Задание 8 (рис. [-@fig:023])

![Самостоятельная работа. Задание 8](image/23.png){ #fig:023 width=70% }

Самостоятельная работа. Задание 9 (рис. [-@fig:024])

![Самостоятельная работа. Задание 9](image/24.png){ #fig:024 width=70% }

Самостоятельная работа. Задание 10 (рис. [-@fig:025])

![Самостоятельная работа. Задание 10](image/25.png){ #fig:025 width=70% }

Самостоятельная работа. Задание 11 (рис. [-@fig:026])

![Самостоятельная работа. Задание 11](image/26.png){ #fig:026 width=70% }

# Выводы

Освоил применение циклов функций и сторонних для Julia
пакетов для решения задач линейной алгебры и работы с матрицами.

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