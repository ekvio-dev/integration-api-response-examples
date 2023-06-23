## Поиск вопросов для тестов с возможностью фильтрации
### Перечень возможных ошибок
| Атрибут | Ошибка                        | Описание                                            |
|---------|:------------------------------|-----------------------------------------------------|
| companyId | Value is required           | Значение для атрибута companyId является обязательным |
| language  | Value is required           | Значение для атрибута language является обязательным |
| id        | Test does not exist         | Тест с идентификатором, который был передан в атрибуте id не найден |
| tests     | Tests must be an integer.   | Значение для атрибута tests должно иметь целочисленный тип |
| tests     | Max count of tests is <max limit>   | Количество переданных значений в атрибуте tests превышает лимит |
| limit     | Limit must be an integer.   | Значение для атрибута limit должно иметь целочисленный тип |
| limit     | Limit must be no less than <min limit>.        | Количество переданных значений в атрибуте limit меньше минимально доступного значения |
| limit     | Limit must be no greater than <max limit>.   | Количество переданных значений в атрибуте limit больше максимально доступного значения |
| filters   | Type field in filter area must be array   | Значение атрибута filters должно иметь тип: массив |
| filters   | The filter area should not be empty   | Значение атрибута filters не должно быть пустым |
| filters   | <type> is unsupported type   | Не поддерживаемый тип внутри аттрибута filters |
### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ошибки недоступности модуля](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/module_unavalible_error.json)
<!-- ### [Пример ответа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/user/login_delete.json) -->