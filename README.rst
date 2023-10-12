|test| |codecov| |docs|

.. |test| image:: https://github.com/intsystems/ProjectTemplate/workflows/test/badge.svg
    :target: https://github.com/intsystems/ProjectTemplate/tree/master
    :alt: Test status
    
.. |codecov| image:: https://img.shields.io/codecov/c/github/intsystems/ProjectTemplate/master
    :target: https://app.codecov.io/gh/intsystems/ProjectTemplate
    :alt: Test coverage
    
.. |docs| image:: https://github.com/intsystems/ProjectTemplate/workflows/docs/badge.svg
    :target: https://intsystems.github.io/ProjectTemplate/
    :alt: Docs status


.. class:: center

    :Название исследуемой задачи:  Статистический анализ корректирующих способностей различных методов при передаче данных в каналах со стираниями
    :Тип научной работы: M1P
    :Автор: Илья Романович Кожанов
    :Научный руководитель: к.ф.-м.н., доцент С.И. Гуров

Abstract
========

В представленной работе осуществляется статистическое моделирование различных методов восстановления стертых пакетов при передаче данных в каналах типа «стирание». Основной целью данного исследования является сравнение методов посредством эмулирования их работы статистическими моделями и подсчетом их корректирующей способности с помощью этих моделей.

Для некоторых методов восстановления пакетов аналитический расчет корректирующей способности невозможен или крайне затруднителен в виду сложной математической модели функционирования данных методов, а также различной эффективности при различных паттернах ошибок. Статистическое моделирование их работы позволяет рассчитать корректирующие способности таких методов и сравнить эффективность их работы. 

В данной рассматриваются метод добавления контрольного пакета четности, его модификация even/odd, коды Рида-Соломона, Фонтанные коды (в частности raptor-коды).


Research publications
===============================
1. 

Presentations at conferences on the topic of research
================================================
1. 

Software modules developed as part of the study
======================================================
1. A python package *mylib* with all implementation `here <https://github.com/intsystems/ProjectTemplate/tree/master/src>`_.
2. A code with all experiment visualisation `here <https://github.comintsystems/ProjectTemplate/blob/master/code/main.ipynb>`_. Can use `colab <http://colab.research.google.com/github/intsystems/ProjectTemplate/blob/master/code/main.ipynb>`_.
