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
### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ошибки недоступности модуля](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/module_unavalible_error.json)