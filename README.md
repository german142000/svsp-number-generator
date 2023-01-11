# svsp-number-generator

Генерация чисел - неотъемлемая часть криптографии. Для генерации чисел в проектах svsp создана php библиотека *svsp-number-generator*, позволяющая
генерировать натуральные числа длиной до 300 символов. Также библиотека позволяет генерировать простые числа (в тестах достигнута длина в 128 символов).

# Функции библиотеки

Библиотека имеет 3 основные функции.

`function random($numlet, $fn, $mn = null, $mx = null)`

Генерирует натуральное число.

- $numlet - максимальное количество символов в числе.
- $fn - если установлено *false* генирируется число с максимальным количеством символов.
- $mn - нижний порог генерации чисел.
- $mx - верхний порог генерации чисел.
