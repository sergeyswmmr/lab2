# Лабораторная работа: Git

Выполнил: Дяченко С.

Основная часть (задания 1-8) сделана в ветке `DyachenkoS`, потом перенесена в `master`.
Программа - `main.py` (Python), вводит два числа и выводит их разность.

Задания со схемами делал в отдельных ветках, чтобы не трогать master:

- `task9-1-merge/master`, `task9-1-merge/test` - схема 1, слияние через merge (коммит C35)
- `task9-2-rebase/master`, `task9-2-rebase/test` - схема 2, через rebase (C4', C5')
- `task9-bonus-merge/...`, `task9-bonus-rebase/...` - то же самое, но C3 и C5 конфликтуют (меняют одну строку в file.txt)
- `task9-1-merge/master` - сверху коммит C67, это задание с двумя изменениями одним коммитом
- `task11/master`, `task11/client`, `task11/server` - последнее задание (rebase --onto)

Граф веток удобно смотреть в Insights -> Network.
