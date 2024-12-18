# Определение жанра музыки по изображению обложки альбома

[ipynb](notebook.ipynb)

## Описание проекта

В данной работе исследована возможность определения жанра музыкального альбома на основе изображения его обложки. Использовались данные с сайта MusicBrainz, включающие 7800 альбомов, разделенных на 10 жанров.

## Навыки и инструменты
*python, scikit-learn, faiss, pytorch, torchvision, fastai* 

## Общий вывод

Была создана нейронная сеть ResNet50, которая достигла точности 65% на тестовых данных, превосходя базовую модель faiss с точностью 48%.
Модель успешно определяет жанры anime, black metal и classic, но испытывает трудности с disco, pop и jazz. Основные проблемы включают переобучение и дисбаланс классов.
Определение жанра по обложке альбома возможно, но требует дальнейшего улучшения модели и расширения набора данных для повышения точности.



