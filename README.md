# clsfction_simpsons
Нейронная сеть для классификации изображений Симпсонов

Домашнее задание от [DLS](https://www.dlschool.org/0). Оно представляет собой [конкурс](https://www.kaggle.com/c/journey-springfield/overview) на платформе kaggle. 

Мною было обучено:

- методом transfer learning модель resnet50 с исходными изображениями и аугментированными
- Простая нейронная сеть с придуманной архитектурой с исходными изображениями и аугментированными

Выводы:
Простая нейронная сеть с архитектурой, состоящей из 5 блоков (Conv2d + RELu + MaxPool2d) и 3 линейными слоями с аугментированнымы изображениями показала наилучший результат.
Наилучший результат определялся по подсчитанному скору на платформе. 

- ResNet50 (16 epochs) without augmentation - 0.80552
- ResNet50 (16 epochs) with augmentation - 0.81934

- SimpleCNN (16 epochs) without augmentation - 0.81827
- SimpleCNN (16 epochs) with augmentation - 0.94580
