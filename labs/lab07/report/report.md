---
## Front matter
title: "Отчет по лабораторной работе №7"
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

Ознакомление с файловой системой Linux, её структурой, именами и содержанием
каталогов. Приобретение практических навыков по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке исполь-
зования диска и обслуживанию файловой системы.


# Выполнение лабораторной работы

выполняю все примеры, приведенные в первой части описания лабораторной работы.(рис. [-@fig:001]).(рис. [-@fig:002]).(рис. [-@fig:003]).(рис. [-@fig:004]).(рис. [-@fig:005]).(рис. [-@fig:006]).

![Выполение команд](image/1.png){#fig:001 width=70%}

![Выполение команд](image/2.png){#fig:002 width=70%}

![Выполение команд](image/3.png){#fig:003 width=70%}

![Выполение команд](image/4.png){#fig:004 width=70%}

![Выполение команд](image/5.png){#fig:005 width=70%}

![Выполение команд](image/6.png){#fig:006 width=70%}

Копирую файл io.h в домашний каталог и называю его equipment.(рис. [-@fig:007]).

![Копирование файла](image/7.png){#fig:007 width=70%}

В домашнем каталоге создаю директорию ski.plases.(рис. [-@fig:008]).

![Создание директории](image/8.png){#fig:008 width=70%}

Перемещаю файл equipment в каталог ski.plases.(рис. [-@fig:009]).

![Перемещение файла](image/9.png){#fig:009 width=70%}

Переименовываю файл equipment в equiplist.(рис. [-@fig:010]).

![Переименование файла](image/10.png){#fig:010 width=70%}

Создаю в домашнем каталоге файл abc1 и копирую его в ski.plases, назвав его equiplist2. (рис. [-@fig:011]).

![Создание файла](image/11.png){#fig:011 width=70%}

Создаю каталог с именем equipment в ski.plases. (рис. [-@fig:012]).

![Создание каталога](image/12.png){#fig:012 width=70%}

Перемещаю файлы equiplist и equiplist2 в каталог equipment. (рис. [-@fig:013]).

![Перемещение файлов](image/13.png){#fig:013 width=70%}

Создаю новый каталог newdir и перемещаю его в ski.plases, назвав его plans. (рис. [-@fig:014]).

![Создание каталога](image/14.png){#fig:014 width=70%}

Определяю операции команды chmod, необходимые для того, чтобы присвоить файлам выделенные права доступа.(рис. [-@fig:015]).(рис. [-@fig:016]).(рис. [-@fig:017]).(рис. [-@fig:018]).

![Выполение команд](image/15.png){#fig:015 width=70%}

![Выполение команд](image/16.png){#fig:016 width=70%}

![Выполение команд](image/17.png){#fig:017 width=70%}

![Выполение команд](image/18.png){#fig:018 width=70%}

Просматриваю содержимое файла /etc/passwd.(рис. [-@fig:019]).

![Просмотр файла](image/19.png){#fig:019 width=70%}

Копирую файл feathers в файл file.old .(рис. [-@fig:020]).

![Копирование файла](image/20.png){#fig:020 width=70%}

Перемещаю файл file.old в каталог play .(рис. [-@fig:021]).

![Перемещение файла](image/21.png){#fig:021 width=70%}

Копирую каталог play в каталог fun.(рис. [-@fig:023]).

![Копирование каталога](image/23.png){#fig:023 width=70%}

Перемешаю каталог fun в play.(рис. [-@fig:024]).

![перемещение каталога](image/24.png){#fig:024 width=70%}

Лишаю владельца файла feathers права на чтение.(рис. [-@fig:025]).

![Лишение прав](image/25.png){#fig:025 width=70%}

Пытаюсь посмотреть файл командой cat.(рис. [-@fig:026]).

![попытка просмотра файла](image/26.png){#fig:026 width=70%}

Пытаюсь скопировать файл feathers.(рис. [-@fig:027]).

![Попытка копирования файла](image/27.png){#fig:027 width=70%}

Даю владельцу право на чтение feathers.(рис. [-@fig:028]).

![Выдача права](image/28.png){#fig:028 width=70%}

Лишаю владельца права на выполение каталога play.(рис. [-@fig:029]).

![Лишение права на выполение](image/29.png){#fig:029 width=70%}

Пытаюсь перейти в каталог play.(рис. [-@fig:030]).

![Попытка перехода в каталог](image/30.png){#fig:030 width=70%}

Даю владельцу право на выполение play.(рис. [-@fig:031]).

![Выдача прав](image/31.png){#fig:031 width=70%}

Читаю man по командам mount,fsck,kill.(рис. [-@fig:032]).

![Чтение man](image/32.png){#fig:032 width=70%}


# Выводы

После выполение данной лабораторной работы я ознакомился с файловой системой linux, её структуройЮ именами и содержанием каталогов.

