---
## Front matter
title: "Отчет по лабораторной работа №10"
subtitle: "Операционные системы"
author: "Намруев Максим Саналовчи"

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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах

# Задание

1. Ознакомиться с теоретическим материалом.
2. Ознакомиться с редактором vi.
3. Выполнить упражнения, используя команды vi


# Выполнение лабораторной работы

Создаю каталог lab10 и перехожу в него(рис. [-@fig:001]).

![Создание каталога](image/1.png){#fig:001 width=70%}

Вызываю vi и создаю файл hello.sh (рис. [-@fig:002]).

![Вызов vi](image/2.png){#fig:002 width=70%}

Нажимаю на клавишу i и ввожу следующий тескт.(рис. [-@fig:003]).

![Ввод текста](image/3.png){#fig:003 width=70%}

Нажмаю калвишу ESC для перехода в командный редим после завершения ввода теста. Записываю и выхожу.(рис. [-@fig:004]).

![Запись и выход](image/4.png){#fig:004 width=70%}

Делаю файл исполняемым(рис. [-@fig:005]).

![Исполняемый файл](image/5.png){#fig:005 width=70%}

Вызываю редактирование текста, перехожу в режим вставки и заменяю HELL на HELLO.(рис. [-@fig:006]).

![Вставка](image/6.png){#fig:006 width=70%}

Ввожу вместо LOCAL local.(рис. [-@fig:008]).

![Замена](image/8.png){#fig:008 width=70%}

Вставляю в последнюю строку echo $HELLO.(рис. [-@fig:009]).

![Последняя строка](image/9.png){#fig:009 width=70%}

Удаляю последнюю строку.(рис. [-@fig:010]).

![Удаление строки](image/10.png){#fig:010 width=70%}

Отменяю последнее действие.(рис. [-@fig:011]).

![Отмена действия](image/11.png){#fig:011 width=70%}

Записываю изменения и выхожу из vi.(рис. [-@fig:012]).

![Выход](image/12.png){#fig:012 width=70%}


# Выводы

После выполнения данной лаьораторной работы я получил практические навыки работы с редактором vi.

