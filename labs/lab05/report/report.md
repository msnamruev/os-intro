---
## Front matter
title: "Отчет по лабораторной работе №5"
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

Настройка рабочей среды.

# Задание

1. Менеджер паролей pass

2. Управление файлами конфигурации

3. Дополнительное программное обеспечение

# Выполнение лабораторной работы

Устанавливаю pass на fedora(рис. [-@fig:001]).

![Установка pass](./image/1.png){#fig:001 width=70%}

Устанавливаю gopass.(рис. [-@fig:002]).

![Установка gopass](./image/2.png){#fig:002 width=70%}

Инициализирую хранилище.(рис. [-@fig:003]).

![Инициализация хранилища](./image/3.png){#fig:003 width=70%}

Создаю структуру git.(рис. [-@fig:004]).

![Создание структуры git](./image/4.png){#fig:004 width=70%}

Для синхронизации хранилища выполняю следующие команды.(рис. [-@fig:005]).

![Синхронизация хранилища](./image/5.png){#fig:005 width=70%}

Делаю изменения непосредственно на файловой системе.(рис. [-@fig:006]).

![Изменения](./image/6.png){#fig:006 width=70%}

Проверю статус модной командой.(рис. [-@fig:007]).

![Проверка статуса](./image/7.png){#fig:007 width=70%}

Устанавливаю расширение на firefox.(рис. [-@fig:008]).

![Установка расширения](./image/8.png){#fig:008 width=70%}

Устанавливаю интерфейс native messaging.(рис. [-@fig:009]).

![Установка интерфейса](./image/9.png){#fig:009 width=70%}

Добавляю новый пароль .(рис. [-@fig:010]).

![Добавление нового пароля](./image/10.png){#fig:010 width=70%}

Заменяю существующий пароль.(рис. [-@fig:011]).

![Замена пароля](./image/11.png){#fig:011 width=70%}

Устанавлюваю доп. программное обеспечение.(рис. [-@fig:012]).

![Установка программного обеспечения](./image/12.png){#fig:012 width=70%}

Устанавливаю бинарный файл .(рис. [-@fig:013]).

![Установка бинарного файла](./image/13.png){#fig:0013 width=70%}

Создаю свой репозиторий на основе шаблона.(рис. [-@fig:014).

![Создание репозитория](./image/14.png){#fig:014 width=70%}

Инициализирую chezmoi с моим репозиторием dotfiles.(рис. [-@fig:015]).

![инициализация chezmoi](./image/15.png){#fig:015 width=70%}

Проверяю какие изменения внесет chezmoi в домашний каталог.(рис. [-@fig:016]).

![Проверка изменений](./image/16.png){#fig:016 width=70%}

Так как меня истраивают изменения запускаю chezmoi apply -v.(рис. [-@fig:017]).

![Запуск](./image/17.png){#fig:017 width=70%}

Извлекаю изменения из репозитория.(рис. [-@fig:018]).

![Извлечение изменений](./image/18.png){#fig:018 width=70%}

# Выводы

После выполнения данной работы я настроил рабочую среду

