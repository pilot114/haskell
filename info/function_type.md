
Все состоит из выражений. Редуцируемые сворачиваються в нередуцируемые.
2+3 -> 5

В Haskell фунции не вызывают, а применяют (apply) к данным.

Тут всё состоит из функции и данных. Они в свою очередь имеют тип и значение.




Функции имеют обычную форму записи и инфиксную:

# simple
sum 1 2
# infix
1 + 2

Можно менять их местами, используя спец.символы:
1 'sum' 2
(+) 1 2


Операторы композиции и применения:
print . checkLocalhost $ "127.0.0.1"