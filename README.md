# Обучение модели Unet ++ на датасете снимков флюорографии

# Что такое UNet++?
Мощная архитектура для сегментации медицинских изображений. Эта архитектура представляет собой сеть кодировщик-декодер с глубоким обучением, в которой подсети кодера и декодера соединены серией вложенных слоев. Переработанные слои направлены на сокращение семантического разрыва между картами признаков подсетей кодировщика и декодера.

# Зависимости
Для сборки UNet++ нам понадобятся: библиотека Tensorflow (глубокое обучение), NumPy (численные вычисления) и skimage (обработка изображений). Также мы будем использовать цветовую палитру matplotlib.

# Задача
В рамках данной работы была проведена сегментация снимков флюорографии.
