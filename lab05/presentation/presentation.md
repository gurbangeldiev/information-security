---
## Front matter
lang: ru-RU
title: Вероятностные алгоритмы проверки чисел на простоту
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

Реализация алгоритмов Ферма, Соловэя-Штрассена, Миллера-Рабина и вычисления Якоби.

# Задачи

## Задачи

1. Реализовать алгоритм Ферма.

2. Реализовать алгоритм Соловэя-Штрассена.

3. Реализовать алгоритм Миллера-Рабина.

4. Реализовать алгоритм вычисления Якоби.

# Реализация

## Реализация алгоритма Ферма

Функция ferma для алгоритма ферма. (рис. -@fig:001)

![Функция для алгоритма ферма](https://github.com/gurbangeldiev/information-security/blob/master/lab05/image/1.png?raw=true){ #fig:001 width=70% }

## Реализация алгоритма для вычисления бинарного эксп

Функция modul для вычисления бинарного эксп. (рис. -@fig:002)

![Функция для вычисления бинарного эксп](https://github.com/gurbangeldiev/information-security/blob/master/lab05/image/2.png?raw=true){ #fig:002 width=70% }

## Реализация алгоритма вычисления Якоби.

Функция jacobian для вычисления Якоби. (рис. -@fig:003)

![Функция для вычисления Якоби](https://github.com/gurbangeldiev/information-security/blob/master/lab05/image/3.png?raw=true){ #fig:003 width=70% }

## Реализация алгоритма Соловэя-Штрассена

Функция solovoy для алгоритма Соловэя-Штрассена. (рис. -@fig:004)

![Функция для алгоритма Соловэя-Штрассена](https://github.com/gurbangeldiev/information-security/blob/master/lab05/image/4.png?raw=true){ #fig:004 width=70% }

## Реализация алгоритма Миллера-Рабина

Функция MillerRabin для алгоритма Миллера-Рабина. (рис. -@fig:005)

![Функция для алгоритма Миллера-Рабина](https://github.com/gurbangeldiev/information-security/blob/master/lab05/image/5.png?raw=true){ #fig:005 width=70% }


## Результат

![Результат алгоритмов](https://github.com/gurbangeldiev/information-security/blob/master/lab05/image/6.png?raw=true){ #fig:006 width=70% }


## Вывод

Реализовал алгоритмы Ферма,Соловэя-Штрассена, Миллера-Рабина и вычисления Якоби.

## {.standout}

Спасибо за внимание
