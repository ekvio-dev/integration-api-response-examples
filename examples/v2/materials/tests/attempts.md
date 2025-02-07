## Экспорт статистики по попыткам пользователей
### Формат ответа
Отчет выгружается в формате **JSON**

### Структура ответа
| Атрибут     | Описание                                                                                    | Типы значений |
|-------------|---------------------------------------------------------------------------------------------|-------------|
| id          | ID попытки                                                                                  | string      |
| material_id | Наименование учетной записи                                                                 | string      |
| login       | Наименование учетной записи                                                                 | string      |
| status      | Статус попытки (fail, completed, checking)                                                  | string      |
| number      | Порядковый номер попытки                                                                    | int / null  |
| points      | Количество баллов                                                                           | int         |
| percent     | Процент прохождения                                                                         | int         |
| q_count     | Общее количество попыток                                                                    | int         |
| q_success     | Количество успешных попыток                                                                 | int         |
| q_fail     | Количество проваленных попыток                                                              | int         |
| q_checking     | Количество попыток на проверке                                                              | int         |
| started_at   | Дата начала попытки. Формат значения Y-m-d\TH:i:sP (например, 2020-12-01T15:52:01+03:00)    | string      |
| ended_at   | Дата окончания попытки. Формат значения Y-m-d\TH:i:sP (например, 2020-12-01T15:52:01+03:00) | string / null |
| created_at   | Дата создания записи. Формат значения Y-m-d\TH:i:sP (например, 2020-12-01T15:52:01+03:00)   | string |
| updated_at   | Дата изменения записи. Формат значения Y-m-d\TH:i:sP (например, 2020-12-01T15:52:01+03:00)  | string |

### Пример
[Пример отчета](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/materials/tests/attempts.json)