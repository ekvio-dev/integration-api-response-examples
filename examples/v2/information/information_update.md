## Обновление материалов в БЗ
### Перечень возможных ошибок
| Атрибут | Ошибка                        | Описание                                            |
|---------|:------------------------------|-----------------------------------------------------|
| id | Value is required | Значение для атрибута id является обязательным |
| id | Information ID does not exist | Значение для атрибута id не найдено в системе |
| companyId | Attribute is required | Значение для атрибута companyId является обязательным |
| companyId | Must be an integer | Значение атрибута companyId должно иметь целочисленный тип |
| category_id | Must be an integer | Значение атрибута category_id должно иметь целочисленный тип |
| category_id | Category ID not exists | Значение для атрибута category_id не найдено в системе |
| category_id | Category must be subcategory | Значение для атрибута category_id должно быть подкатегорией |
| name | Must be a string | Значение атрибута name должно иметь строковый тип |
| type | Type is invalid.    | Значение для атрибута type не валидно |
| description | Must be a string | Значение атрибута description должно иметь строковый тип |
| status | Status is invalid.    | Значение для атрибута status не валидно |
| content | Must be string | Значение атрибута content должно иметь строковый тип |
| content | Сannot be blank | Значение для атрибута content не может быть пустым |
| language | Limit must be an integer. | Значение атрибута language должно иметь строковый тип |
| file_token | Must be a string | Значение атрибута file_token должно иметь строковый тип |
| image_token | Must be a string | Значение атрибута image_token должно иметь строковый тип |
| filename | Must be a string | Значение атрибута filename должно иметь строковый тип |
### [Пример ответа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/information/information_update.json)