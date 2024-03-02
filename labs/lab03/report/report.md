---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Операционные системы"
author: "Намруев Максим Саналович"

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
mainfont: PT Sans
romanfont: PT Sans
sansfont: PT Sans
monofont: PT Sans
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

1. Сделайте отчёт по предыдущей лабораторной работе в формате Markdown.
2. В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md (в архиве, поскольку он должен содержать скриншоты, Makefile и т.д.)

# Выполнение лабораторной работы

Перехожу в папку с лабораторной работой №2 и открываю файл report.md через утилиту gedit.(рис. [-@fig:001]).

![Открытие файла](/home/msnamruev/Изображения/Снимки экрана/1.png){#fig:001 width=70%}

После открытия начинаю заполнение отчета.рис. [-@fig:002])

![Начало заполнения отчета](/home/msnamruev/Изображения/Снимки экрана/2.png){#fig:002 width=70%}

После завершения написания отчета, сохраняю файл и конвертирую его в форматы pdf и docx.рис. [-@fig:003])

![Конвертирование файла](/home/msnamruev/Изображения/Снимки экрана/3.png){#fig:003 width=70%}

Далее отправляю файлы на GitHub.рис. [-@fig:004])

![Отправка файлов на GitHub](/home/msnamruev/Изображения/Снимки экрана/4.png){#fig:004 width=70%}

# Выводы

После завершения данной лабораторной работы я научился работать с легковесным языком разметки Markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
