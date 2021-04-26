## Экспорт статистики по заданиям
### Формат ответа
Отчет выгружается в формате **JSON**

###Структура ответа
| Атрибут |Описание| Типы значений |
| -------| ----- | ---- |
| task | ID задания | int |
| login | Наименование учетной записи пользователя | string |
| answer | ID ответа пользователя | int |
| status | Статус  ответа (checking, completed, failed) | string |
| comment | Комментарий к ответу пользователя | string |
| created_at | Дата создания ответа | string |
| fields | Список ответов на вопросы | array |

### Структура ответов на вопросы задания (атрибут fields)
| Атрибут |Описание| Типы значений |
| -------| ----- | ---- |
| id | ID вопроса | int |
| value | Значение ответа | string | null |

### Пример
[Пример отчета](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/tasks/tasks-statistic.json)