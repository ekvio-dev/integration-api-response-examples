## Создание материалов в БЗ
### Перечень возможных ошибок
| Атрибут | Ошибка                        | Описание                                            |
|---------|:------------------------------|-----------------------------------------------------|
| companyId | Attribute is required | Значение для атрибута companyId является обязательным |
| companyId | Must be an integer | Значение атрибута companyId должно иметь целочисленный тип |
| category_id | Attribute is required | Значение для атрибута category_id является обязательным |
| category_id | Must be an integer | Значение атрибута category_id должно иметь целочисленный тип |
| name | Attribute is required | Значение для атрибута name является обязательным |
| name | Must be a string | Значение атрибута name должно иметь строковый тип |
| description | Must be a string | Значение атрибута description должно иметь строковый тип |
| status | Attribute is required | Значение для атрибута status является обязательным |
| status | Status is invalid.    | Значение для атрибута status не валидно |
| content | Attribute is required | Значение для атрибута content является обязательным |
| content | Must be string | Значение атрибута content должно иметь строковый тип |
| content | Сannot be blank | Значение для атрибута content не может быть пустым |
| file_token | Must be a string | Значение атрибута file_token должно иметь строковый тип |
| image_token | Must be a string | Значение атрибута image_token должно иметь строковый тип |
| filename | Must be a string | Значение атрибута filename должно иметь строковый тип |
### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ошибки недоступности модуля](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/module_unavalible_error.json)
### [Пример ответа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/information/information_create.json)