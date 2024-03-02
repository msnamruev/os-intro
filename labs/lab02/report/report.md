---
## Front matter
title: "Отчет по лабораторной работе №2"
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


1. Изучить идеологию и применение средств контроля версий.

2. Освоить умения по работе с git.


# Задание

1. Установка программного обеспечения

2. Базовая настройка git

3. Создание ключи ssh

4. Создание ключи pgp

5. Настройка github

6. Добавление PGP ключа в GitHub

7. Настройка автоматических подписей коммитов git

8. Настройка gh



# Выполнение лабораторной работы

## Установка программного обеспечения

Открываю терминал и устанавливаю git (рис. [-@fig:001]).

![Установка git](/home/msnamruev/Изображения/Снимки экрана/3.png){#fig:001 width=70%}

Далее устанавливаю gh.(рис. [-@fig:002])

![Установка gh](/home/msnamruev/Изображения/Снимки экрана/4.png){#fig:002 width=70%}

## Базовая настройка git

Задаю имя и email владельца репозитория, а также настраиваю utf-8 в выводе сообщений git, задаю имя начальной ветки, настраиваю параметр autocrlf и safecrlf.(рис. [-@fig:003])

![Базовая настройка git](/home/msnamruev/Изображения/Снимки экрана/5.png){#fig:003 width=70%}

## Создание ключи ssh

Создаю ssh ключ по алгоритму rsa с размером 4096 бит.(рис. [-@fig:004])

![Создание ssh ключа по алгоритму rsa](/home/msnamruev/Изображения/Снимки экрана/6.png){#fig:004 width=70%}

Создаю ssh ключ по алгоритму ed25519.(рис. [-@fig:005])

![Создание ssh ключа по алгоритму ed25519](/home/msnamruev/Изображения/Снимки экрана/7.png){#fig:005 width=70%}

##  Создание ключи pgp

Генерирую pgp ключ.В предложенных опциях выбираю: тип RSA and RSA, размер 4096 и срок действия по умолчанию.(рис. [-@fig:006])

![Генерация pgp ключа](/home/msnamruev/Изображения/Снимки экрана/8.png){#fig:006 width=70%}

Далее ввожу личную информацию (Имя, адрес электронной почты).(рис. [-@fig:007])

![Заполнение личной информации](/home/msnamruev/Изображения/Снимки экрана/9.png){#fig:007 width=70%}

## Настройка github

Создаю учетную запись на github и заполняю основные данные. (рис. [-@fig:021])

![Создание учетной записи на github](/home/msnamruev/Изображения/Снимки экрана/23.png){#fig:021 width=70%}

## Добавление PGP ключа в GitHub

Вывожу список ключей.(рис. [-@fig:008])

![Вывод ключа](/home/msnamruev/Изображения/Снимки экрана/10.png){#fig:008 width=70%}

Копирую мой сгенерированный PGP ключ в буфер обмена.(рис. [-@fig:009])

![Копирование pgp ключа](/home/msnamruev/Изображения/Снимки экрана/11.png){#fig:009 width=70%}

Перехожу в настройки GitHub, нажимаю на кнопку New GPG key и вставляю полученный ключ в полу ввода.(рис. [-@fig:010])

![Присоединение ключа к github](/home/msnamruev/Изображения/Снимки экрана/12.png){#fig:010 width=70%}

Используя введёный email, указываю Git применять его при подписи коммитов.(рис. [-@fig:011]) (рис. [-@fig:012])

![Указание применения email](/home/msnamruev/Изображения/Снимки экрана/13.png){#fig:011 width=70%}

![Указание применения email](/home/msnamruev/Изображения/Снимки экрана/14.png){#fig:012 width=70%}

## Настройка gh

Авторизуюсь в gh.(рис. [-@fig:013])

![Авторизация](/home/msnamruev/Изображения/Снимки экрана/15.png){#fig:013 width=70%}

Создаю шаблон рабочего пространства. Для этого создаю нужные каталоги.(рис. [-@fig:014])

![Создание шаблона](/home/msnamruev/Изображения/Снимки экрана/16.png){#fig:014 width=70%}

Создаю репозиторий на GitHub.(рис. [-@fig:015])

![Создания репозитория на Github](/home/msnamruev/Изображения/Снимки экрана/17.png){#fig:015 width=70%}

Далее клонирую репозиторий.(рис. [-@fig:016])

![Клонирование репозитоия](/home/msnamruev/Изображения/Снимки экрана/18.png){#fig:016 width=70%}

Перехожу в каталог курса и удаляю лишние файлы.(рис. [-@fig:017])

![Удаление ненужных файлов](/home/msnamruev/Изображения/Снимки экрана/19.png){#fig:017 width=70%}

Создаю необходимые каталоги.(рис. [-@fig:018])

![Создание каталогов](/home/msnamruev/Изображения/Снимки экрана/20.png){#fig:018 width=70%}

Отправляю файлы на сервер.(рис. [-@fig:019])(рис. [-@fig:020])

![Отправка файлов на сервер](/home/msnamruev/Изображения/Снимки экрана/21.png){#fig:019 width=70%}

![Отправка файлов на сервер](/home/msnamruev/Изображения/Снимки экрана/22.png){#fig:19 width=70%}

# Выводы

После выполнение данной лабораторной работы я изучил идеологию и применение средств контроля версий и освоил умения по работе с git

# Список литературы{.unnumbered}

::: {#refs}
:::
