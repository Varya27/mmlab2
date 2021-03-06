---
## Front matter
lang: ru-RU
title: задача о погоне
author: |Голова Варвара
group: "НФИбд-03-18"
ID: "1032182507"

institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
date: 2021, 18 february
## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
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
![Первый случай, часть 1](images/lab2_1.jpg){ #fig:001 width=70% }
![Первый случай, часть 2](images/lab2_2.jpg){ #fig:002 width=70% }

Программный код для второго случая (x2=5, tetha_0=-pi) (рис. -@fig:003 и рис. -@fig:004).
![Второй случай, часть 1](images/lab2_3.jpg){ #fig:003 width=70% }
![Второй случай, часть 2](images/lab2_4.jpg){ #fig:004 width=70% }


## Результаты для первого случая

Общий вывод для первого случая (x1=3, tetha_0=0) (рис. -@fig:005).
![Первый случай](images/lab2_5.jpg){ #fig:005 width=70% }

## Результаты для второго случая

Общий вывод для второго случая (x1=5, tetha_0=-pi) (рис. -@fig:006).
![Второй случай](images/lab2_6.jpg){ #fig:006 width=70% }

## Точки пересечения

В первом случае точка пересечения: r=13, tetha=320. В втором случае точка пересечения: r=48, tetha=320.


# Выводы

Я озакомилась со способом решения задачи о погоне и решила ее
