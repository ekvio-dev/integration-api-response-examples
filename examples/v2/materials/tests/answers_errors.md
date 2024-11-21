## Экспорт списка ответов пользователей на вопросы тестов программы обучения
### Перечень возможных ошибок
| Атрибут | Ошибка                        | Описание                                            |
|---------|:------------------------------|-----------------------------------------------------|
| companyId | Value is required           | Значение для атрибута companyId является обязательным |
| language  | Value is required           | Значение для атрибута language является обязательным |
| userStatus       | User Status is invalid.         | Значение для атрибута userStatus не валидно |
| materialStatus   | Material Status is invalid. | Значение для атрибута materialStatus не валидно |
| filters   | Filter question is required   | Значение атрибута filters должно иметь тип: массив |
| filters   | Filter with_reset must be boolean | Значение атрибута with_reset для атрибута filters должно иметь булевый тип |
| filters   | Filter question must be array   | Значение атрибута filters должно иметь тип: массив |
| filters   | Filter question has not integer elements   | Тип значений question для атрибута filters не соответствует допустимому |
| filters   | Filter question elements count is greater <max limit>   | Количество значений question для атрибута filters превышает максимально допустимый лимит |
| filters   | Filter login elements count is greater <max limit> | Количество значений login для атрибута filters превышает максимально допустимый лимит |
| filters   | Filter question_type must be array | Тип question_type для атрибута filters не соответствует допустимому |
| filters   | Filter question_type has not string elements | Тип значений question_type для атрибута filters не соответствует допустимому |
| filters   | Filter question_type has not valid type. Allowed types: mcq, select-image, open-question |  |
| filters   | Filter answer_status must be array | Тип answer_status для атрибута filters не соответствует допустимому |
| filters   | Filter answer_status has not string elements | Тип значений answer_status для атрибута filters не соответствует допустимому |
| filters   | Filter answer_status has not valid status. Allowed statuses: success, fail, checking, not_answer | Значения answer_status для атрибута filters не соответствуют допустимому |
| afterDate | Invalid value format. Valid Y-m-d\TH:i:sP | Не валидный формат для атрибута afterDate |
| toDate    | Invalid value format. Valid Y-m-d\TH:i:sP | Не валидный формат для атрибута toDate |
### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ошибки недоступности модуля](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/module_unavalible_error.json)