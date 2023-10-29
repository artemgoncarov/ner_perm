# ner

Проект решает задачу поиска именованных сущностей в названии и описании на сервисе RuTube. В проекте целых 2 модели!

# Архитектура решения

![Архитектура]([https://github-production-user-asset-6210df.s3.amazonaws.com/61351134/271807159-6b5c9b29-c0da-4e43-b148-a8d651b9aa38.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20231001%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231001T033737Z&X-Amz-Expires=300&X-Amz-Signature=5b861136006557f4df68a67daa6031d7e68dd538aa26b5a3396d34a510cb80d1&X-Amz-SignedHeaders=host&actor_id=61351134&key_id=0&repo_id=698162921](https://i.imgur.com/H4zxOFb.jpg))

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
