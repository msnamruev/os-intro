---
## Front matter
title: "Отчет по лабораторной работе №6"
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

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки

# Выполнение лабораторной работы

Определяю полное имя мое домашнего каталога (рис. [-@fig:001]).

![Определение полного имени домашнего каталога](image/1.png){#fig:001 width=70%}

Перехожу в каталог /tmp и вывожу его содержимое разными командами.(рис. [-@fig:002]).(рис. [-@fig:003]).(рис. [-@fig:004]).

![Вывод содержимого /tmp](image/2.png){#fig:002 width=70%}

![Вывод содержимого /tmp](image/3.png){#fig:003 width=70%}

![Вывод содержимого /tmp](image/4.png){#fig:004 width=70%}

Определяю есть ли в каталоге /var/spool подкаталог и именем cron (рис. [-@fig:005]).

![Определение наличия подкаталога](image/5.png){#fig:005 width=70%}

Перехожу в мой домашний каталог и вывожу на экран его содержимое, определяя, кто является владельцем файлов.(рис. [-@fig:006]).

![Вывод содержимого домашнего каталога](image/6.png){#fig:006 width=70%}

Создаю каталог newdir(рис. [-@fig:007]).

![Создание каталога](image/7.png){#fig:007 width=70%}

В нем создаю каталог morefun(рис. [-@fig:008]).

![Создание каталога в каталоге](image/8.png){#fig:008 width=70%}

Далее одной командой создаю 3 каталога и удаляю их(рис. [-@fig:009]).

![Создание и удаление 3 каталогов одной командой](image/9.png){#fig:009 width=70%}

Пытаюсь удалить каталог newdir командой rm(рис. [-@fig:010]).

![Попытка удаление каталога](image/10.png){#fig:010 width=70%}

Удаляю каталог morefun.(рис. [-@fig:011]).

![Удаление каталога morefun из домашнего каталога](image/11.png){#fig:011 width=70%}

Определяю с помощью какой команды можно вывести сожержимое не только указаного каталога, но и подкаталогов(рис. [-@fig:012]).

![Определение опции](image/12.png){#fig:012 width=70%}


С помощью команды man определяю  набор опций команды ls, позволяющий отсортировать по времени последнего изменения выводимый список содержимого каталога с развёрнутым описанием файлов(рис. [-@fig:013]).

![Определение опции](image/13.png){#fig:013 width=70%}

Использую команду man для просмотра описания команд cd, pwd, mkdir, rmdir, rm.(рис. [-@fig:014]).

![Просмотр опций](image/14.png){#fig:014 width=70%}

выполняю модификацию и исполнение команды из буфера команд(рис. [-@fig:015]).

![Модификация команд](image/15.png){#fig:015 width=70%}

# Выводы

После выполнения данной лабораторной работы я приобрел навыки взаимодействия пользователя с системой посредством командной строки

