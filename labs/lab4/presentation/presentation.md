---
## Front matter
lang: ru-RU
title: Лабораторная работа №4
subtitle: Дискреционное разграничение прав в Linux. Расширенные атрибуты
author:
  - Карпова Е.А.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 19.03.2025

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
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Карпова Есения Алексеевна
  * Студентка НКАбд-02-23
  * ФФМиЕН
  * Российский университет дружбы народов
  * [1132236008@pfur.ru](mailto:1132236008@pfur.ru)
  * <https://github.com/eakarpova>

:::
::: {.column width="30%"}

![](image/me.jpeg)

:::
::::::::::::::

# Вводная часть

## Цели и задачи

# Выполнение лабораторной работы

## Определение атрибутов файла

- `lsattr /home/guest/dir1/file1`
- `chmod 600 file1 `
- `chattr +a /home/guest/dir1/file1`

## Проверка установки атрибутов

![](image/5.jpg)

## Дозапись в файл

![](image/6.jpg)

## Удаление файла

![](image/7.jpg)

## Смена прав

- `chmod 000 file1`
- `chattr -a /home/guest/dir1/file1`

## Повтор операций

![](image/11.jpg)

## Попытка смены атрибута

![](image/12.jpg)

## Замена атрибута от суперпользователя

![](image/13.jpg)

## Выполнение команд

![](image/14.jpg)

