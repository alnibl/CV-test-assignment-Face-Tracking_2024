# Анализ Демографии Посетителей

## Описание проекта
Данный проект реализует систему для оценки демографии посетителей торговых центров или ресторанов. 
Система использует детекцию и трекинг лиц на видеопотоке с веб-камеры для последующего определения возраста и пола каждого посетителя.

## Цель проекта:

- Детектировать лица на видеопотоке.
- Трекать обнаруженные лица, чтобы не считать одного и того же посетителя несколько раз.
- Выбирать "лучшее" лицо из каждого трека для дальнейшего анализа.

**Примечание**: В текущей версии проекта выбор "лучшего" лица из трека не реализован.

## Технологии и инструменты
- Язык программирования: Python 3.8
- Библиотеки:
  - ultralytics==8.2.41
  - omegaconf==2.3.0
  - flask==3.0.3

## Настройка окружения
### Для Linux
Создайте и активируйте виртуальное окружение:
- python3 -m venv venv
- source venv/bin/activate

Установите зависимости:
- make install

### Для Windows
Создайте и активируйте виртуальное окружение:
- python -m venv venv
- venv\Scripts\activate
- 
Установите зависимости:
- make install
**Примечание**: Убедитесь, что у вас установлен инструмент make на Windows. Если make отсутствует, вы можете установить зависимости напрямую:
-pip install -r requirements.txt
