# Домашнее задание 1

## Условие

Реализовать четыре модуля, реализующие функции троичной логики, на языке Verilog:
* `min`
* `max`
* `consensus`
* `any`

Таблицы истинности эти функций могут быть найдены в [презентации](https://slides.com/romanmelnikov/deck-1#/21).

Трит кодируется с помощью двух бит:
* `-` - 00
* `0` - 01
* `+` - 10

В качестве решения необходимо прислать файл `ternary_logic.v`, в котором будут реализованы
фунцкии для троичной логики, а также все необходимые примитивы.

В данном задании запрещено использование встроенных логических примитивов, их необходимо реализовать
самостоятельно с помощью транзисторов.

Шаблон для реализации: [`ternary_logic.v`](./tern/ternary_logic.v).

Ваше решение должно собираться при помощи `iverilog -g2001 ternary_logic.v`.
