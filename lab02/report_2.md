---
# Front matter
lang: ru-RU
title: "Отчет по лабораторной работе №1"
subtitle: "Работа с Git. Язык Markdown"
author: "Голова Варвара Алексеевна"
group: "НФИбд-03-18"
ID: "1032182507"


# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
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

Ознакомиться с задачей о погоне и решить ее.

# Задание

Записать уравнение, описывающее движение катера, с начальными
условиями для двух случаев (в зависимости от расположения катера
относительно лодки в начальный момент времени).
Построить траекторию движения катера и лодки для двух случаев.
Найти точку пересечения траектории катера и лодки.


# Выполнение лабораторной работы

## Расчеты

Рассчитала, что для k=15 и n=4, x1=15/5=3, x2=15/3=5, тангенциальная скорость равна sqrt(15)*v

## Программный код

Программный код для первого случая (x1=3, tetha_0=0) (рис. -@fig:001 и рис. -@fig:002).
![Первый случай, часть 1](image/lab2_1.jpg){ #fig:001 width=70% }
![Первый случай, часть 2](image/lab2_2.jpg){ #fig:002 width=70% }

Программный код для второго случая (x2=5, tetha_0=-pi) (рис. -@fig:003 и рис. -@fig:004).
![Второй случай, часть 1](image/lab2_3.jpg){ #fig:003 width=70% }
![Второй случай, часть 2](image/lab2_4.jpg){ #fig:004 width=70% }

## Результаты

Общий вывод для первого случая (x1=3, tetha_0=0) (рис. -@fig:005).
![Первый случай](image/lab2_5.jpg){ #fig:005 width=70% }

Общий вывод для второго случая (x1=5, tetha_0=-pi) (рис. -@fig:006).
![Второй случай](image/lab2_6.jpg){ #fig:006 width=70% }

## Точки пересечения

В первом случае точка пересечения: r=13, tetha=320. В втором случае точка пересечения: r=48, tetha=320.


# Выводы

Я озакомилась со способом решения задачи о погоне и решила ее
