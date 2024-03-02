---
## Front matter
title: "Индивидуальный проект Этап 1"
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

Размещение на Github pages заготовки для персонального сайта.

# Задание


1. Установить необходимое программное обеспечение.
   
2. Скачать шаблон темы сайта.
   
3. Разместить его на хостинге git.
    
4. Установить параметр для URLs сайта.
    
5. Разместить заготовку сайта на Github pages.


# Теоретическое введение

# Выполнение лабораторной работы

Скачиваю архив приложения hugo (рис. [-@fig:001]).

![Скачивание архива](./image/1.png){#fig:001 width=70%}

Разархивирую архив.(рис. [-@fig:002]).

![Разархивирование](./image/2.png){#fig:002 width=70%}

Переношу приложение hugo в /usr/local/bin.(рис. [-@fig:003]).

![Перенос приложения](./image/3.png){#fig:003 width=70%}

Создаю новый репозиторий по шаблону (blog).(рис. [-@fig:004]).

![Создание репозитория](./image/4.png){#fig:004 width=70%}

Клонирую репозитоий в blog.(рис. [-@fig:005]).

![Клонирование репозитоия](./image/5.png){#fig:005 width=70%}

Скачиваю разширение go.(рис. [-@fig:006]).

![Скачивание go](./image/6.png){#fig:006 width=70%}

Прописываю команду hugo server, создавая сайт локально.(рис. [-@fig:007]).

![Создание сайта](./image/7.png){#fig:007 width=70%}

Перехожу по ссылке и проверяю создание сайта.(рис. [-@fig:008]).

![Проверка сайта](./image/8.png){#fig:008 width=70%}

Создаю ещё один репозиторий без шаблона (msnamruev.github.io).(рис. [-@fig:009]).

![Создание нового репозитория](./image/9.png){#fig:009 width=70%}

Клонирую его.(рис. [-@fig:010]).

![Клонирование репозитория](./image/10.png){#fig:010 width=70%}

Перехожу в него и переключаюсь на новую ветку "main".(рис. [-@fig:011]).

![Переключение на новую метку](./image/11.png){#fig:011 width=70%}

Создаю файл README.md и отправляю данные на github.(рис. [-@fig:012]).

![Отправка на github](./image/12.png){#fig:012 width=70%}

Далее с помощью mc перехожу в gitignore и комментирую public.(рис. [-@fig:013]).

![комментирование](./image/13.png){#fig:013 width=70%}

Далее удаляю папку public и клонирую репозиторий в новую папку public.(рис. [-@fig:014]).

![Копирование репозитория](./image/14.png){#fig:014 width=70%}

Запускаю приложение hugo.(рис. [-@fig:015]).

![Запуск приложения](./image/15.png){#fig:015 width=70%}

Перехожу в папку public и проверяю корректность выполнения работы запуска приложения.(рис. [-@fig:016]).

![Проверка](./image/16.png){#fig:016 width=70%}

Отправляю данные по github.(рис. [-@fig:017]).(рис. [-@fig:018]).

![отправка данных](./image/17.png){#fig:017 width=70%}

![отправка данных](./image/18.png){#fig:018 width=70%}

И наконец проверяю работу сайта.(рис. [-@fig:019]).

![Проверка работы сайта](./image/19.png){#fig:019 width=70%}

# Выводы

После выполнения данного этапа я разместил на github pages заготовки для персонального сайта

# Список литературы{.unnumbered}

::: {#refs}
:::
