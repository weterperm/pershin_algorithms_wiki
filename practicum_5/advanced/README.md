 

# **Задача о раскраске Графа**

### Обязательно смотрите прикрепеленные pdf файлы

> *Описание задачи*
> Даны граф G=⟨V,E⟩ и число k. Необходимо проверить, правда ли, что можно раскрасить вершины графа в k цветов так, чтобы любые две вершины, соединённые ребром, имели разные цвета.

![.](https://w7.pngwing.com/pngs/867/829/png-transparent-graph-coloring-graph-theory-vertex-mathematics-mathematics-angle-triangle-symmetry-thumbnail.png)

> Зачастую количество цветов меньше хроматического числа, что требует поиска решения, минимизирующего количество конфликтов, то есть количество ребер с узлами одинаковых цветов. Кроме того, раскраска графов в общем случае является NP-сложной задачей. 5

## Основная часть

### *Эвристические алгоритмы* 

> почитать про них можно в отдельном файле в той же директории

#### Решение через random search algorithm

> просто меняем случайную вершину/группу вершин и проверяем с помощью функции ошибки

#### Решение через [Поиск восхождением к вершине (Hill Climbing)

> Это не единственный вариант решения, но на числах больше никакие другие алгоритмы не справляются

####  Решение через Метод Имитации Отжига (Simulated annealing)

> Это не единственный вариант решения, но на числах больше никакие другие алгоритмы не справляются



## Именно решение через Метод Имитации Отжига является нашей задачей

