## Создание индивидуальных назначений для мероприятий
### Перечень возможных ошибок
| Атрибут | Ошибка                        | Описание                                            |
|---------|:------------------------------|-----------------------------------------------------|
| event | event value required.       | Значение для атрибута event является обязательным |
| event | event value must be number. | Значение для атрибута event должно быть числовым  |
| event | Event does not exist        | ID мероприятия не существует                          |
| event | Individual assignment is already exists.        | Индивидуальное назначение уже существует            |
| login   | login value required.         | Значение для атрибута login является обязательным   |
| login   | login value must be string.   | Значение для атрибута login должно быть строковым   |
| login   | Login does not exist   | Пользователь с таким login не существует            |

### [Пример ошибки для параллельного запуска задач одного типа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/uniq_task_error.json)
### [Пример ошибки недоступности модуля](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/module_unavalible_error.json)
### [Пример ответа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/event/event-assignment-create.json)