# Исключения. ЭТАП_6

## Описание задачи

__Проблема:__ при инициализации экземпляра класса `Video` пользователь может передать несуществующий id видео. 

Внедрите в код блоки `try/except` , чтобы отловить исключение `HttpError`.
```python
from googleapiclient.errors import HttpError
```

Если пользователь передал id, с которым невозможно получить данные о видео по API, 
то у экземпляра инициализируется только свойство `video_id`, а остальные поля принимают значение `None`.

## Ожидаемое поведение
- Код в файле `main.py` должен выдавать ожидаемые значения
