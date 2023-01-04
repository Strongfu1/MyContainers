# MyContainers in C++

## Description

Данный проект содержит в себе частичную реализацию шаблонных контейнеров по заданию School 21:

Container | Name | Realisation on
--- | --- | --- |
array | s21::array | static array |
vector | s21::vector | dynamic array |
queue | s21::queue | linked list |
stack | s21::stack | linked list |
list | s21::list | double linked list |
map | s21::map | red black tree |
set | s21::set | red black tree |
multiset | s21::multiset | red black tree |

## Testing

Для выполнения всех тестов, проверки проходимости кода и проверок на утечки:

```bash
make tests
```

Для компиляции тестов отдельного контейнера

```bash
make s21_set
```

где set - может быть любым контейнером.
