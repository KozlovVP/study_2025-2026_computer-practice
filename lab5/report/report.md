---
## Front matter
title: "Отчёт по лабораторной работе №5"
subtitle: "Построение графиков"
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

Освоить синтаксис языка Julia для построения графиков

# Задание

1. Используя Jupyter Lab, повторите примеры из раздела 5.2. При этом дополните графики
обозначениями осей координат, легендой с названиями траекторий, названиями
графиков и т.п.
2. Выполните задания для самостоятельной работы (раздел 5.4).

# Выполнение лабораторной работы

Задание 5.2.1 (рис. [-@fig:001])

![Задание 5.2.1](image/1.png){ #fig:001 width=70% }

Задание 5.2.1 (рис. [-@fig:002])

![Задание 5.2.1](image/2.png){ #fig:002 width=70% }

Задание 5.2.2 (рис. [-@fig:003])

![Задание 5.2.2](image/3.png){ #fig:003 width=70% }

Задание 5.2.3 (рис. [-@fig:004])

![Задание 5.2.3](image/4.png){ #fig:004 width=70% }

Задание 5.2.3 (рис. [-@fig:005])

![Задание 5.2.3](image/5.png){ #fig:005 width=70% }

Задание 5.2.4 (рис. [-@fig:006])

![Задание 5.2.4](image/6.png){ #fig:006 width=70% }

Задание 5.2.5 (рис. [-@fig:007])

![Задание 5.2.5](image/7.png){ #fig:007 width=70% }

Задание 5.2.6 (рис. [-@fig:008])

![Задание 5.2.6](image/8.png){ #fig:008 width=70% }

Задание 5.2.7 (рис. [-@fig:009])

![Задание 5.2.7](image/9.png){ #fig:009 width=70% }

Задание 5.2.8 (рис. [-@fig:010])

![Задание 5.2.8](image/10.png){ #fig:010 width=70% }

Задание 5.2.9 (рис. [-@fig:011])

![Задание 5.2.9](image/11.png){ #fig:011 width=70% }

Задание 5.2.12 (рис. [-@fig:012])

![Задание 5.2.12](image/12.png){ #fig:012 width=70% }

Задание 5.2.13 (рис. [-@fig:013])

![Задание 5.2.13](image/13.png){ #fig:013 width=70% }

Задание 5.2.14 (рис. [-@fig:014])

![Задание 5.2.14](image/14.png){ #fig:014 width=70% }

Задание 5.4.1 (рис. [-@fig:015])

![Задание 5.4.1](image/15.png){ #fig:015 width=70% }

Задание 5.4.2 (рис. [-@fig:016])

![Задание 5.4.2](image/16.png){ #fig:016 width=70% }

Задание 5.4.3 (рис. [-@fig:017])

![Задание 5.4.3](image/17.png){ #fig:017 width=70% }

Задание 5.4.4 (рис. [-@fig:018])

![Задание 5.4.4](image/18.png){ #fig:018 width=70% }

Задание 5.4.5 (рис. [-@fig:019])

![Задание 5.4.5](image/19.png){ #fig:019 width=70% }

Задание 5.4.6 (рис. [-@fig:020])

![Задание 5.4.6](image/20.png){ #fig:020 width=70% }

Задание 5.4.7 (рис. [-@fig:021])

![Задание 5.4.7](image/21.png){ #fig:021 width=70% }

Задание 5.4.8 (рис. [-@fig:022])

![Задание 5.4.8](image/22.png){ #fig:022 width=70% }

Задание 5.4.9 (рис. [-@fig:023])

![Задание 5.4.9](image/23.png){ #fig:023 width=70% }

Задание 5.4.10 (рис. [-@fig:024])

![Задание 5.4.10](image/24.png){ #fig:024 width=70% }

Задание 5.4.11 (рис. [-@fig:025])

![Задание 5.4.11](image/25.png){ #fig:025 width=70% }

# Выводы

Освоил синтаксис языка Julia для построения графиков.

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