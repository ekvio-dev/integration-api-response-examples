## Создание индивидуальных назначений для сущности
### Перечень возможных ошибок
| Атрибут | Ошибка                        | Описание                                            |
|---------|:------------------------------|-----------------------------------------------------|
| id | id value required.       | Значение для атрибута id является обязательным |
| id | id value must be number. | Значение для атрибута id должно быть числовым  |
| id | Id does not exist        | ID сущности не существует                          |
| id | Individual assignment is already exists.        | Индивидуальное назначение уже существует            |
| login   | login value required.         | Значение для атрибута login является обязательным   |
| login   | login value must be string.   | Значение для атрибута login должно быть строковым   |
| login   | Login does not exist   | Пользователь с таким login не существует            |

### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ошибки недоступности модуля](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/module_unavalible_error.json)
### [Пример ответа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/assignment/create-assignment.json)