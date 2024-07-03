## Экспорт статистики по траекториям
### Формат ответа
Отчет выгружается в формате **JSON**
### Структура ответа
| Атрибут |Описание| Типы значений |
| -------| ----- | ---- |
| id | ID траектории | int |
| name | Название траектории обучения | string |
| max_points | Общее количество баллов за траекторию | int |
| user_status | Статус пользователя | string |
| status | Статус прохождения | string |
| start_date | Дата начала прохождения. Формат значения Y-m-d\TH:i:sP (например, 2023-12-01T15:52:01+03:00) | string / null |
| active_at | Дата последней активности. Формат значения Y-m-d\TH:i:sP (например, 2023-12-02T15:52:01+03:00) | string / null |
| end_at | Дата окончания прохождения. Формат значения Y-m-d\TH:i:sP (например, 2023-12-03T15:52:01+03:00) | string / null |
| passed_at_time | Наименовение учетной записи | bool / null |
| points | Набранное количество баллов | int |
| objects_amount | Всего материалов в траектории | int |
| objects_passed | Пройдено материалов в траектории | int |
| global_progress | Глобальный прогресс | int |
| progress_in_moment | Прогресс на момент выгрузки | int |

### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ошибки недоступности модуля](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/module_unavalible_error.json)
### [Пример отчета](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/tracks/track-statistic-response.json)