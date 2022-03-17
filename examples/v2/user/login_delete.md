## Удаление пользователей
### Перечень возможных ошибок
| Атрибут | Ошибка                        | Описание                                            |
|---------|:------------------------------|-----------------------------------------------------|
| login      | Value is required                  | Значение для атрибута login является обязательным |
| login      | Value must be string               | Значение для атрибута login должно быть строкой |
| login      | Value should be at most <max limit> symbols | Длина значения атрибута login превышает 50 символов |
| login      | Value should be at least <min limit> symbols | Длина значения атрибута login меньше 1 символа |
| login      | Login does not exist               | Логин не существует |

### [Пример ответа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/user/login_delete.json)