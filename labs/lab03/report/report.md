---
## Front matter
title: "Отчет по лабораторной работе №3"
subtitle: "Дисциплина: Компьютерные науки и технологии программирования"
author: "Бодунков Алексей Павлович"

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

# Цель работы

Целью работы является освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

# Выполнение лабораторной работы

Переход в каталог arch-pc и затем в lab03 вместе с обновление репозитория на устройстве (рис. [-@fig:001]).

![Обновление локального репозитория и переход в каталог lab03](image/обновление локального репозитория и переход в lab03.png){ #fig:001 width=70% }

Создание файлов шаблона с помощью команды make (рис. [-@fig:002]).

![Компиляция шаблона](image/Создание файлов с помощью команды make.png){ #fig:002 width=70% }

Удаление полученных файлов и проверка, что они были удалены (рис. [-@fig:003]).

![Удаление файлов](image/удаление файлов с помощью make clean.png){ #fig:003 width=70% }

Открытие файла report.md с помощью текстового редактора gedit (рис. [-@fig:004]).

![Открытие файла с шаблоном отчета](image/Открытие файла в gedit.png){ #fig:004 width=70% }

Заполнение отчета и компилирование его с использованием Makefile. Отчет в трех форматах предоставлен. 

# Выполнение самастоятельной работы

Был выполнен 2-ой отчёт через Markdown(отправлен в ТУИС как просроченная сдача второй Лабараторной, загружен на репозиторий Github там же).

# Выводы

Я освоил процедуры оформления отчетов с помощью языка разметки Markdown.

# Ссылка на репозиторий Github

https://github.com/Valtrus/study_2023-2024_arh-pc
