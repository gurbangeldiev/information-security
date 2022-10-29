---
## Front matter
lang: ru-RU
title: Вычисление наибольшего общего делителя
author: |
	Гурбангельдиев Мухаммет \inst{1}

institute: |
	\inst{1}RUDN University, Moscow, Russian Federation

date: 2022 Moscow, Russia

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

## цель работы

Реализация алгоритмов вычисления наибольшего общего делителя (Евклида).

# Задачи

## Задачи

1. Реализовать алгоритм Евклида.

2. Реализовать бинарный алгоритм Евклида.

3. Реализовать расширенный алгоритм Евклида.

4. Реализовать расширенный бинарный алгоритм Евклида.

# Реализация

## Реализация алгоритма Евклида

Функция evklid_nod для вычисления алгоритма Евклида. (рис. -@fig:001)

![Функция для вычисления алгоритма Евклида](https://github.com/gurbangeldiev/information-security/blob/master/lab04/images/1.png?raw=true){ #fig:001 width=70% }

## Реализация бинарного алгоритма Евклида

Функция evklid_binary для вычисления бинарного алгоритма Евклида. (рис. -@fig:002)

![Функция для вычисления бинарного алгоритма Евклида](https://github.com/gurbangeldiev/information-security/blob/master/lab04/images/2.png?raw=true){ #fig:002 width=70% }

## Реализация расширенного алгоритма Евклида.

Функция evklid_extend для вычисления расширенного алгоритма Евклида. (рис. -@fig:003)

![Функция для вычисления вычисления расширенного алгоритма Евклида.](https://github.com/gurbangeldiev/information-security/blob/master/lab04/images/3.png?raw=true){ #fig:003 width=70% }

## Реализация расширенного бинарного алгоритма Евклида.

Функция evklid_binary_extend для вычисления расширенного бинарного алгоритма Евклида. (рис. -@fig:004) (рис. -@fig:005)

![Функция для вычисления расширенного бинарного алгоритма Евклида. Первая часть](https://github.com/gurbangeldiev/information-security/blob/master/lab04/images/4.png?raw=true){ #fig:004 width=60% }

##

![Функция для вычисления расширенного бинарного алгоритма Евклида. Вторая часть](https://github.com/gurbangeldiev/information-security/blob/master/lab04/images/5.png?raw=true){ #fig:005 width=70% }

# Результат

## Результат

![Результат алгоритмов](https://github.com/gurbangeldiev/information-security/blob/master/lab04/images/6.png?raw=true){ #fig:006 width=70% }


## Вывод

Реализовал алгоритм вычисления наибольшего общего делителя (Евклида).

## {.standout}

Спасибо за внимание
