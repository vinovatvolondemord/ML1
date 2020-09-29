# Нелинейные методы восстановления регрессии
Общая идея в том, что задача сводится к решению последовательности более простых линейных задач.
Пусть задана нелинейная модель регрессии ![](https://latex.codecogs.com/gif.latex?f%28x%2C%5Calpha%29) и требуется минимизироватьфункционал качества по вектору параметров ![](https://latex.codecogs.com/gif.latex?%5Calpha%5Csubset%5Cmathbb%7BR%7D%5Ep):

![](https://latex.codecogs.com/gif.latex?Q%28%5Calpha%2CX%5El%29%3D%5Csum_%7Bi%3D1%7D%5El%28f%28x_i%2C%5Calpha%29-y_i%29%5E2)

