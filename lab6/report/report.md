---
## Front matter
title: "Отчёт по лабораторной работе №6"
subtitle: "Решение моделей в непрерывном и дискретном времени"
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

Основной целью работы является освоение специализированных пакетов для решения
задач в непрерывном и дискретном времени.

# Задание

1. Используя Jupyter Lab, повторите примеры из раздела 6.2.
2. Выполните задания для самостоятельной работы (раздел 6.4).

# Выполнение лабораторной работы

Библиотеки (рис. [-@fig:001])

![Библиотеки](image/1.png){ #fig:001 width=70% }

Экспоненциальный рост (рис. [-@fig:002])

![Экспоненциальный рост](image/2.png){ #fig:002 width=70% }

Повышенная точность (рис. [-@fig:003])

![Повышенная точность](image/3.png){ #fig:003 width=70% }

Система Лоренца (рис. [-@fig:004])

![Система Лоренца](image/4.png){ #fig:004 width=70% }

Модель Лотки-Вольтерры (рис. [-@fig:005])

![Модель Лотки-Вольтерры](image/5.png){ #fig:005 width=70% }

Задание №2 (рис. [-@fig:006])

![Задание №2](image/6.png){ #fig:006 width=70% }

Задание №3 (рис. [-@fig:007])

![Задание №3](image/7.png){ #fig:007 width=70% }

Задание №4 (рис. [-@fig:008])

![Задание №4](image/8.png){ #fig:008 width=70% }

Задание №5 (рис. [-@fig:009])

![Задание №5](image/9.png){ #fig:009 width=70% }

Задание №5 (рис. [-@fig:010])

![Задание №5](image/10.png){ #fig:010 width=70% }

Задание №6 (рис. [-@fig:011])

![Задание №6](image/11.png){ #fig:011 width=70% }

График (рис. [-@fig:012])

![График](image/12.png){ #fig:012 width=70% }

Задание №7 (рис. [-@fig:013])

![Задание №7](image/13.png){ #fig:013 width=70% }

График (рис. [-@fig:014])

![График](image/14.png){ #fig:014 width=70% }

Задание №8 (рис. [-@fig:015])

![Задание №8](image/15.png){ #fig:015 width=70% }

График (рис. [-@fig:016])

![График](image/16.png){ #fig:016 width=70% }

Задание №9 (рис. [-@fig:017])

![Задание №9](image/17.png){ #fig:017 width=70% }

График (рис. [-@fig:018])

![График](image/18.png){ #fig:018 width=70% }

# Выводы

Освоил специализированные пакеты для решения
задач в непрерывном и дискретном времени.

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