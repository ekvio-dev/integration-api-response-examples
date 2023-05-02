## Переименование логинов пользователей
### Перечень возможных ошибок
| Атрибут | Ошибка                        | Описание                                            |
|---------|:------------------------------|-----------------------------------------------------|
| companyId | Value is required                  | Значение для атрибута companyId является обязательным |
| from      | Value is required                  | Значение для атрибута from является обязательным |
| from      | Value must be string               | Значение для атрибута from должно быть строкой |
| from      | Value should be at most <max limit> symbols | Длина значения атрибута from превышает 50 символов |
| from      | Value should be at least <min limit> symbols | Длина значения атрибута from меньше 1 символа |
| from      | Login not exists                   | Исходный логин для переименования из значения атрибута from не существует |
| to        | Value is required                  | Значение для атрибута to является обязательным |
| to        | Value must be string               | Значение для атрибута to должно быть строкой |
| to        | Value should be at most <max limit> symbols | Длина значения атрибута from превышает 50 символов |
| to        | Value should be at least <min limit> symbols | Длина значения атрибута from меньше 1 символа |
| to        | Bad login format                   | Значение для атрибута to не соответствует формату логина |
| to        | Login is already exists            | Конечный логин для переименования из значения атрибута to уже существует |

### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ответа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/user/login_rename.json)