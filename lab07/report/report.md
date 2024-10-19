---
## Front matter
title: "Лабораторная работа № 7"
subtitle: "Элементы криптографии. Однократное гаммирование"
author: "Форис Анастасия Дмитриевна"

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
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
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

## Цель работы
Освоить на практике применение режима однократного гаммирования.

## Выполнение лабораторной работы

Код программы (рис.7).

![Рис. 7:Приложение, реализующее режим однократного гаммирования](image/lab7.png)


• In[21]: импорт необходимых библиотек
• In[22]: функция, реализующая сложение по модулю два двух строк
• In[23]: открытый/исходный текст
• In[24]: создание ключа той же длины, что и открытый текст
• In[25]: получение шифротекста с помощию функции, созданной ранее, при
условии, что известны открытый текст и ключ
• In[26]: получение открытого текста с помощью функции, созданной ранее,
при условии, что известны шифротекст и ключ
• In[27]: получение ключа с помощью функции, созданной ранее, при условии,
что известны открытый текст и шифротекст


## Выводы

В ходе выполнения данной лабораторной работы я освоила на практике применение режима однократного гаммирования.

