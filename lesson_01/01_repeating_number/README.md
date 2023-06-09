# B. Повторяющееся число

Вам дана последовательность измерений некоторой величины. Требуется определить, повторялась ли какое-либо число, причём расстояние между повторами не превосходило *k*.

## Формат ввода

В первой строке задаются два числа *n* и *k* *(1 ≤ n, k ≤ 10^5)*.

Во второй строке задаются *n* чисел, по модулю не превосходящих *10^9*.

## Формат вывода

Выведите YES, если найдется повторяющееся число и расстояние между повторами не превосходит *k* и NO в противном случае.

## Примеры

### Пример №1

#### Ввод

```shell
4 2
1 2 3 1
```

#### Вывод

```shell
NO
```

### Пример №2

#### Ввод

```shell
4 1
1 0 1 1
```

#### Вывод

```shell
YES
```

### Пример №3

#### Ввод

```shell
6 2
1 2 3 1 2 3
```

#### Вывод

```shell
NO
```
