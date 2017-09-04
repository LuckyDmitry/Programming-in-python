Python очень активно применяют ученые со всего мира в своих исследованиях. В этом задании мы с вами попробуем с помощью Python найти корни квадратного уравнения.

Напомним, что квадратное уравнение выглядит следующим образом:

1[](https://github.com/avtomato/Programming-in-python/blob/master/img/R0aLunqZEeeOygpRbdVQKg_1dd9788a7c74533091fed7514159f0dd_q-eqn.png)

На вход программе мы подадим коэффициенты a, b и c - ваша цель напечатать 2 корня квадратного уравнения (каждый с новой строки).

Если вы не помните формулу (а мы и сами ее не помним!), позволяющую найти корни такого уравнения, обратитесь за помощью к статье в [Википедии](https://ru.wikipedia.org/wiki/%D0%9A%D0%B2%D0%B0%D0%B4%D1%80%D0%B0%D1%82%D0%BD%D0%BE%D0%B5_%D1%83%D1%80%D0%B0%D0%B2%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5).

Чтобы не усложнять вашу задачу все коэффициенты, которые мы будем подавать вам на вход являются коэффициентами, которые в итоге дают 2 целых корня квадратного уравнения.

Коэффициенты a, b, c вы можете получить следующим образом:
```python
import sys
a = int(sys.argv[1])
b = int(sys.argv[2])
c = int(sys.argv[3])
```
Вывод вашей программы для коэффициентов a = 1, b = -3, c = -4:
```python
-1
4
```
Корни должны быть приведены к целочисленному виду перед выводом на экран, порядок вывода корней произвольный. Успехов в решении!