## Экспорт статистики по персональным данным
### Формат ответа
Отчет выгружается в формате **JSON**

###Структура ответа
| Атрибут |Описание| Типы значений |
| -------| ----- | ---- |
| login | Наименование учетной записи пользователя | string |
| status | Статус персональных дданых (confirm, check) | string / null|
| filled_at | Дата заполнения (метка времени timestamp) | int |
| answers | Структура ответов | array |

### Структура ответов (атрибут answers)
| Атрибут |Описание| Типы значений |
| -------| ----- | ---- |
| question_id | ID вопроса | int |
| external_key | Внешний символьный код вопроса | string |
| type | Тип вопроса (number, textfield, email, phone, select, date, file_upload) | string | null |
| value | Значение ответа пользователя | string |

### Пример
[Пример отчета](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/personal/personal-statistic.json)