
В своем алгоритме я использовала пять слоёв:
1) Dense(256)
2) Dense(128)
3) Dense(64)
4) Dense(64)
5) Dense(32)
Слои Dense используют активацию relu, кроме последнего слоя. Нейронная сеть проходит 10 эпох обучения.

В обучении используется:

1) Функция потерь
2) Метрика accuracy
3) Оптимизатор adam

![Loss function](https://github.com/VictoriaIL/SMOMI_LAB1/blob/master/Loss.png)
![Accuracy function](https://github.com/VictoriaIL/SMOMI_LAB1/blob/master/Accuracy.png)
accurancy = 0.4800

