# Задача предсказания рейтинга научной статьи

## 1. Описание:
Задача состоит в том, что по данным об авторе, его персональному рейтингу, рейтингу журнала, параметрам статьи и другим статистикам определить будущий рейтинг статьи, которую он представит.

Данные записаны в csv-файле:
![image](https://user-images.githubusercontent.com/45245696/149194414-8f3e05f0-9425-4a3b-85e5-e494a42d3ea6.png)

## 2. Технологии решения:
- Python 3
- Pandas
- Numpy
- Matplotlib
- Sklearn, catboost

## 3. Используемая модель и результаты:
- Использовались модели:
  - Линейная регрессия с L1 и L2-регуляризацией
  - Дерево решений
  - Ансамбли
  - Случайный лес
  - Градиентный бустинг
- Лучний результат:
  - Градиентный бустинг с r2_score равным 0.73

Результат успешный, так как минимальное требование для данной задачи было r2_score = 0.5

Тестовое задание от JetBrains

## 4. Гайд по настройке

- В файле project.yml находится окружение, в котором установлены пакеты Python 3.8.8,
sklearn, pandas, numpy

- Чтобы принять это окружение, необходимо выполнить в anaconda navigator (в текущей директории) команды в файле start.txt

- Запустите блокнот, выполните все строки

- Удалите окружение с помощью команд, описанных в файле end.txt
