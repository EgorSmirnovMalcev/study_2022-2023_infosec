---
## Front matter
lang: ru-RU
title: Основы информационной безопасности
subtitle: Лабораторная работа № 3. Дискреционное разграничение прав в Linux. Два пользователя
author:
  - Смирнов-Мальцев Е. Д.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 21 сентября 2024

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Смирнов-Мальцев Егор Дмитриевич
  * студент группы НКНбд-01-21
  * Российский университет дружбы народов
  
:::
::::::::::::::

# Цель работы

Получение практических навыков работы в консоли с атрибутами файлов для групп пользователей.

# Теоретическое введение

В Linux можно задавать права не только для себя и всех пользователей, но и для группы пользователей. Это можно делать с помощью команды chmod.

# Выполнение лабораторной работы

Добавления гостевого пользователя

![](image/1.png){#fig:001 width=70%}

## Вывод команд groups и id

![](image/2.png){#fig:001 width=70%}

## Информация о гостевом пользователе в файле /etc/group

![Информация о гостевом пользователе](image/3.png){#fig:003 width=70%}

## Информация о группах второго гостевого пользователя

![](image/4.png){#fig:004 width=70%}

## Изменение прав директорий

![](image/5.png){#fig:005 width=70%}

## Проверка входа в директории

![](image/6.png){#fig:006 width=70%}

# Выводы

Получена информация о доступе к файлам.
