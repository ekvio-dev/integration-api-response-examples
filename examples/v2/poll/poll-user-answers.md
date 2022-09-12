## Экспорт ответов пользователей на вопросы опроса
### Формат ответа
Отчет выгружается в формате **JSON**
### Структура ответа
| Атрибут     | Описание                                                                | Типы значений |
|-------------|-------------------------------------------------------------------------|---------------|
| question_id | ID вопроса                                                              | int           |
| login       | Наименовение учетной записи                                             | string        |
| answers     | Список выбранных вариантов ответа. Пустой массив, если ответов не было. | array         |
| comment     | Комментарий пользователя                                                | string / null |