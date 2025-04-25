
[Блокнот для отладки](https://colab.research.google.com/drive/14eustLc7SVBtMesemDSqQoNeP216GmiK?usp=sharing)

[Основной блокнот](https://colab.research.google.com/drive/1hynKWtUuC5U-MRNtAyA-0Q-XuNAUDLTW?usp=sharing)

[Импорт MedMNIST и фильтрация отдельного класса](https://colab.research.google.com/drive/1qxXjec9gg5NgH0FEVoedgyRbZBk5b7GX?usp=sharing)



**Обучение генеративных состязательных сетей (generative adversarial network – GAN)**

В ходе выполнения лабораторной работы необходимо обучить GAN для генерации изображений кошек. В случае успешного выполнения задачи полученный подход нужно применить для синтеза медицинских изображений.
В качестве обучающей выборки удобно использовать подходящую базу из [MedMNIST](https://medmnist.com/).
Для лучшего качества генерируемых изображений из базы MedMNIST можно отфильтровать один класс и обучаться только на этих изображениях.
Пример фильтрации приведен [здесь](https://colab.research.google.com/drive/1qxXjec9gg5NgH0FEVoedgyRbZBk5b7GX?usp=sharing).

Лабораторная работа основана на материалах задания курса [CS 444 Deep Learning for Computer Vision](https://slazebni.cs.illinois.edu/spring24/).

С исходными материалами и инструкциями можно познакомиться [здесь](https://slazebni.cs.illinois.edu/spring24/assignment4.html).

[Ссылка на оригинальную базу изображений кошек cats.zip](https://drive.google.com/file/d/1z6rgdKhJINmriXNJ_bUsTdsefoHh2QFD/view?usp=sharing)

[Основной блокнот](https://colab.research.google.com/drive/1hynKWtUuC5U-MRNtAyA-0Q-XuNAUDLTW?usp=sharing) – основной jupyter-блокнот для обучения GAN генерации изображений кошек (в блокноте есть указания, какие фрагменты необходимо дополнить).

[Блокнот для отладки](https://colab.research.google.com/drive/14eustLc7SVBtMesemDSqQoNeP216GmiK?usp=sharing) – вспомогательный jupyter-блокнот для отладки кода (для быстроты обучения используется MNIST и упрощенная модель). Блокнот позволит верифицировать, корректен ли код функций потерь и код обучения.

Обучать GAN можно любым удобным способом (google colab, kaggle, локально) с применением GPU для ускорения вычислений.
В случае использования для обучения google colab для быстрой загрузки изображений правильнее распаковать архив с изображениями в хранилище текущего сеанса (как это сделано в текущей реализации) и читать изображения из полученной папки, а не считывать их напрямую из google drive (разместив там папку с изображениями).
