## Экспорт статистики по компетенциям
### Формат ответа
Отчет выгружается в формате **JSON**
### Структура ответа
| Атрибут |Описание| Типы значений |
| -------| ----- | ---- |
| competency_id | ID компетенции | int |
| login | Наименовение учетной записи | string |
| value | Уровень развития компетенции | int |
### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ошибки недоступности модуля](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/module_unavalible_error.json)