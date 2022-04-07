## Создание категории в БЗ
### Перечень возможных ошибок
| Атрибут | Ошибка                        | Описание                                            |
|---------|:------------------------------|-----------------------------------------------------|
| status | Invalid status | Статус из атрибута status не поддерживается |
| companyId | Company Id must be an integer. | Значение атрибута companyId должно иметь целочисленный тип |
| language | Language must be an integer. | Значение атрибута language должно иметь целочисленный тип |
| description | Value must be string | Значение атрибута description должно иметь строковый тип |
| parent_id | Parent id does not exist | Значение атрибута parent_id не существует |
| parent_id | Parent id is subcategory already | Значение атрибута parent_id уже является подкатегорией |
### [Пример ответа](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/information/information_category_create.json)