## Изменение статуса ответа пользователя на задания с открытым ответом
### Перечень возможных ошибок
| Атрибут | Ошибка                        | Описание                                            |
|---------|:------------------------------|-----------------------------------------------------|
| id | Attribute is required | Значение для атрибута id является обязательным  |
| id | Answer id does not exist | Задание с идентификатором из атрибута id не найдено  |
| id | Attribute must be string | Значение для атрибута id должно иметь строковый тип  |
| status | Attribute is required | Значение для атрибута status является обязательным |
| status | Unsupported task answer status | Статус из атрибута status не поддерживается |
| status | Attribute must be string | Значение для атрибута status должно иметь строковый тип |
| mark | Attribute is required | Значение для атрибута mark является обязательным |
| mark | Attribute must be string | Значение для атрибута mark должно иметь строковый тип |
| mark | Limit must be no less than <min limit>.        | Количество переданных значений в атрибуте mark меньше минимально доступного значения |
| mark | Limit must be no greater than <max limit>.   | Количество переданных значений в атрибуте mark больше максимально доступного значения |
| comment | Max length comment is <max limit> characters | Значение для атрибута comment превышает установленный максимальный лимит |
### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ошибки недоступности модуля](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/module_unavalible_error.json)
### [Пример ответа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/learning-program/open-question-verification.json)