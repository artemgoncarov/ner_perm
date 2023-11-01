# ner

Проект решает задачу поиска именованных сущностей в названии и описании на сервисе RuTube. В проекте целых 2 модели!

# Архитектура решения

![Архитектура](https://i.imgur.com/H4zxOFb.jpg)

# Пример

## Реальное

> Катаю десятки. 
Открываю контейнеры. 
Вечерний стрим с kalashnikoff22rus
 Катаю 10 ки. 
Получаю контейнеры с оборудкой. 
Открываю их между катками. 
Разбираю ошибки свои , 
сокомандников и ворога. 
Также удачные позиции для домага. 
Приятных просмотров. 
Подписывайтесь на наш канал


## Именованные сущности

> [‘word’: ‘kalashnikoff22rus’, ‘class’: 'I-название проекта']

# Использованные технологии

- Google Colab
- PyTorch
- Tensorflow
- transformers
- spaCy
- sklearn

# Описания файлов

- модель на spaCy - [ссылка](https://github.com/artemgoncarov/ner_perm/blob/main/spacy.ipynb)
- модель на tensorflow - [ссылка](https://github.com/artemgoncarov/ner_perm/blob/main/tenser-ner.ipynb)

# Работали над проектом:

- [Андреасян Егор](https://github.com/EgorAndrik)
- Алехин Андрей
- [Гончаров Артём](https://github.com/artemgoncarov)
