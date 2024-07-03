## Обновление материалов в Медиатеке
### Перечень ошибок
| Атрибут        | Ошибка                        | Описание                                            |
|----------------|:------------------------------|-----------------------------------------------------|
| category_id    | Attribute is required | Значение для атрибута category_id является обязательным |
| category_id    | Must be an integer | Значение атрибута category_id должно иметь целочисленный тип |
| name           | Attribute is required | Значение для атрибута name является обязательным |
| name           | Must be a string | Значение атрибута name должно иметь строковый тип |
| description    | Must be a string | Значение атрибута description должно иметь строковый тип |
| status         | Status is invalid | Значение для атрибута status не валидно |
| image_token    | Must be a string | Значение атрибута image_token должно иметь строковый тип |
| video_sd_token | Must be a string | Значение атрибута video_sd_token должно иметь строковый тип |
| video_hd_token | Must be a string | Значение атрибута video_hd_token должно иметь строковый тип |
### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ошибки недоступности модуля](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/module_unavalible_error.json)
### [Пример ответа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/media/media_update.json)