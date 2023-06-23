## Обновление категории в БЗ
### Перечень возможных ошибок
| Атрибут | Ошибка                        | Описание                                            |
|---------|:------------------------------|-----------------------------------------------------|
| id | Value is required | Значение для атрибута id является обязательным |
| status | Invalid status | Статус из атрибута status не поддерживается |
| name | Value must be string | Значение атрибута name должно иметь строковый тип |
| name | Value should be at most <max limit> symbols | Длинна атрибута name превышает допустимый максимальный предел |
| description | Value must be string | Значение атрибута description должно иметь строковый тип |
| parent_id | Parent id does not exist | Значение атрибута parent_id не существует |
| parent_id | Parent id is subcategory already | Значение атрибута parent_id уже является подкатегорией |
### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ошибки недоступности модуля](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/module_unavalible_error.json)
### [Пример ответа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/information/information_category_update.json)