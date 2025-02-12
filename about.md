---
layout: page
title: Про курс
description: Загальна інформація.
nav_order: 1
---

# Про курс
{:.no_toc}

## Зміст
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{% assign overview = site.slides | where: "title", "Огляд" | first %}
{{ overview.content }}


Потрiбнi навички
: - Рівень володіння англійською мовою не нижче А2.
- **Математика**: знання та вміння використовувати обчислення, аналітичну геометрію, лінійну алгебру та теорію ймовірностей.
- **Програмування**: написання коду на Python.

Підручники
: 1. Кочура Ю. П. (2025). [Еволюцiйнi обчислення](https://www.dropbox.com/scl/fi/o4ev3maxdrcax9ka95anh/main-0.0.1.pdf?rlkey=uvb5enqpperpi5nsnb1uvs3cf&st=44gzb2qf&dl=0). Посiбник перебуває на етапi написання.
1. Wirsansky, E. (2020). [Hands-on genetic algorithms with Python: applying genetic algorithms to solve real-world deep learning and artificial intelligence problems](https://download.packt.com/free-ebook/9781838557744). Packt Publishing Ltd.
1. Micheal Lanham. (2023). [Evolutionary Deep Learning: Genetic algorithms and neural networks](https://www.manning.com/books/evolutionary-deep-learning).


## На випадок повітряної тривоги
{% assign siren = site.slides | where: "title", "Повітряна тривога" | first %}
{{ siren.content }}

## Особливостi
{% assign specifics = site.slides | where: "title", "Особливостi" | first %}
{{ specifics.content }}

## Система оцiнювання
{% assign grading = site.slides | where: "title", "Система оцiнювання" | first %}
{{ grading.content }}


## Кодекс честi
{% assign honorcode = site.slides | where: "title", "Кодекс честi" | first %}
{{ honorcode.content }}


## Як успішно завершити курс?
{% assign succeed = site.slides | where: "title", "Як успішно завершити курс?" | first %}
{{ succeed.content }}