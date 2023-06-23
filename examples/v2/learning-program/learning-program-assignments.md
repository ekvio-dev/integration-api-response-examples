## Поиск назначений по программам обучения с возможностью фильтрации
### Перечень возможных ошибок
| Атрибут | Ошибка                        | Описание                                            |
|---------|:------------------------------|-----------------------------------------------------|
| company_id | Value is required | Значение для атрибута company_id является обязательным |
| language | Value is required | Значение для атрибута language является обязательным |
| type | Value is required | Значение для атрибута id является обязательным |
| page | Must be an integer |  Значение атрибута page должно иметь целочисленный тип |
| perPage | Must be an integer | Значение атрибута perPage должно иметь целочисленный тип |
| perPage | Limit must be no less than 100. | Количество переданных значений в атрибуте perPage меньше минимально доступного значения |
| perPage | Limit must be no greater than 10000. | Количество переданных значений в атрибуте perPage больше максимально доступного значения |
| filters | Program filter must be array | Значение атрибута filters должно иметь тип: массив |
| filters | Program filter elements count is greater 500 | Количество переданных значений в атрибуте filters больше максимально доступного значения |
| filters | Login filter must be array | Значение login внутри атрибута filters должно иметь тип: массив |
| filters | Login filter elements count is greater 500 | Количество переданных значений в login для атрибуте filters больше максимально доступного значения |

### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ошибки недоступности модуля](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/module_unavalible_error.json)
<!-- ### [Пример ответа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/information/information-statistic.json) -->