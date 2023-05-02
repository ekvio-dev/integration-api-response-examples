## Экспорт статистики по базе знаний
### Формат ответа
Отчет выгружается в формате **JSON**

### Структура ответа
| Атрибут |Описание| Типы значений |
| -------| ----- | ---- |
| id | ID материала обучения базы знаний | int |
| login | Наименование учетной записи | string |
| viewed_at | Дата просмотра материала. Формат значения Y-m-d\TH:i:sP (например, 2020-12-01T15:52:01+03:00) | string / null |

### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ошибки недоступности модуля](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/module_unavalible_error.json)
### Пример
[Пример отчета](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/information/information-statistic.json)