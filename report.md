---
# Front matter
lang: ru-RU
title: "Отчёт по лабараторной работе №1"
subtitle: ""
author: "Кученов Ирзилей Сайын Вячеславович, преподаватель: Кулябов Дмитрий Сергеевич"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Ознакомление с git и github.

# Задание

Выполнить следующие пункты:
1) Создание логина на гитхабе
2) Загрузка ssh ключей на него
3) Создание и загрузка каталогов
4) Правильный формат коммитов
5) Создание релиза на гитхабе
6) Создание отчёта
7) Помещение отчета в сорсы
8) Закачка всего на гитхаб вместе с отчетом
9) Создание финального релиза

# Выполнение лабораторной работы

1. Создание логина на гитхабе:
Создаю логин вводя команды:
git config --global user.name "Your Name"
git config --global user.email "your_email@whatever.com"

![Создание логина](image/login.jpg){ #fig:001 width=70% }

2. Создание и загрузка каталога:
![Создание и загрузка каталога](image/repository.jpg){ #fig:001 width=70% }

3. Коммиты
Вносим изменения в html файл, подтверждаем и индексируем изменения.
![Коммиты](image/commit.jpg){ #fig:001 width=70% }

4. Генерация SSH ключей
![SSH ключи](image/ssh.jpg){ #fig:001 width=70% }

5. Создание релиза на гитхабе
![Релиз](image/release.jpg){ #fig:001 width=70% }

6. Cоздание отчёта
![Отчёт](image/report.jpg){ #fig:001 width=70% }

7. 

# Выводы

Здесь кратко описываются итоги проделанной работы.
