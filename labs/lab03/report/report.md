---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Язык разметки Markdown"
author: "Власов Артем Сергеевич"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Ознакомиться с языком разметки Markdown и оформить отчет по лабораторной работе №2 в ней.

# Задание

Сформировать отчет по лабораторной работе №2 с помощью Markdown.

# Выполнение лабораторной работы №3

Переходим в каталог, который привязан к репозиторию Git на сайте Github. (рис. @fig:001).

![Переходим в нужный каталог](image/1.png){#fig:001 width=70%}

С помощью команды git pull обновляем локальный репозиторий,скачивая изменения. (рис. @fig:002).

![Используем команду git pull](image/2.png){#fig:002 width=70%}

Переходим в каталог report 3 лабораторной работы. (рис. @fig:003).

![Переходим в следующий каталог](image/3.png){#fig:003 width=70%}

Используем команду make для создания файлов report.pdf и report.docx (рис. @fig:004).

![Используем команду make](image/28.png){#fig:004 width=70%}

Проверяем, как сработала команда make (рис. @fig:005).

![Открывем файлы и проверяем создание документов](image/4.png){#fig:005 width=70%}

Используем команду make clean, которая удаляет недавно созданные документы(рис. @fig:006).

![Используем команду make clean](image/5.png){#fig:006 width=70%}

Открываем файлы и смотрим, сработала ли команда make clean(рис. @fig:007).

![Проверяем,как сработала команда make clean](image/6.png){#fig:007 width=70%}

Используем команду gedit report.md, которая открывает редактор данного документа (рис. @fig:008).

![Используем команду gedit](image/7.png){#fig:008 width=70%}

Изучаем открывшийся файл(рис. @fig:009).

![Изучаем документ](image/8.png){#fig:009 width=70%}

Изучив структуру файла, начинаем его изменять(рис. @fig:010).

![Изменяем документ](image/9.png){#fig:010 width=70%}

# Делаем отчет лабораторной работы №2

Делаем предварительную конфигурацию git. (рис. @fig:011).

![Задаем имя и email репозитория](image/10.png){#fig:011 width=70%}

Настраиваем utf-8 в выводе сообщения git. (рис. @fig:012).

![Настраиваем utf-8](image/11.png){#fig:012 width=70%}

Задаем имя начальной ветки. (рис. @fig:013).

![Задаем имя начальной ветки, как master](image/12.png){#fig:013 width=70%}

![Устанавливаем настройку autocrlf](image/13.png){#fig:014 width=70%}

![Устанавливаем параметр safecrlf](image/14.png){#fig:015 width=70%}

Создаем SSH ключ(рис. @fig:016).

![Генерируем пару ключей командой keygen](image/15.png){#fig:016 width=70%}

![Копируем ключ из локальной консоли в буфер обмена](image/16.png){#fig:017 width=70%}

Заходим в свой аккаунт на сайте github. Переходим в настройки, SSH ключи. (рис. @fig:018).

![вставляем ключ и сохраняем](image/17.png){#fig:018 width=70%}

![Проверяем добавление ключа](image/18.png){#fig:019 width=70%}

Открываем терминал и создаем каталоги для предмета "Архитектура компьютера"(рис. @fig:020).

![Создаем каталоги последовательно](image/19.png){#fig:020 width=70%}

Переходим на страницу репозитория с шаблоном(рис. @fig:021).

![Создаем репозиторий по шаблону](image/20.png){#fig:021 width=70%}

Переходим в папку с предметом(рис. @fig:022).

![Переходим в каталог курса](image/21.png){#fig:022 width=70%}

![Клонируем созданный репозиторий](image/22.png){#fig:023 width=70%}

Переходим в каталог arch-pc(рис. @fig:024).

![Переходим в нужный каталог](image/23.png){#fig:024 width=70%}

![Удаляем лишние файлы](image/24.png){#fig:025 width=70%}

Создаем папки по образцу(рис. @fig:026).

![Создаем необходимые каталоги](image/25.png){#fig:026 width=70%}

Отправляем файлы на сервер(рис. @fig:027).

![Отправляем фалы на git](image/26.png){#fig:027 width=70%}

Отправляем прошлую лабораторную работу(рис. @fig:028).

![Проверяем отправку ЛБ1](image/27.png){#fig:028 width=70%}

# Выводы

Мы познакомились с языком разметки Markdown и оформили отчет в ней и загрузили на Github.
