## Экспорт статистики по курсам
### Формат ответа
Отчет выгружается в формате **JSON**

### Структура ответа
| Атрибут |Описание| Типы значений |
| -------| ----- | ---- |
| user_id | ID пользователя | int |
| material_id | ID материала курса | int |
| fio | Фамилия имя отчество пользователя | string |
| user_status | Статус учетной записи пользователя (active, blocked) | string |
| login | Наименование учетной записи пользователя | string |
| start_time | Дата начала прохождения курса. Формат значения Y-m-d\TH:i:sP (например, 2020-12-01T15:52:01+03:00) | string / null |
| complete_date | Дата окончания прохождения курса. Формат значения Y-m-d\TH:i:sP (например, 2020-12-01T15:52:01+03:00) | string / null |
| total_time | Общее время, затраченное на прохождение купса. Значение по умолчанию 0. | int |
| name | Наименование курса | string / null|
| is_required | Обязательность курса | int |
| user_scores | Количество набранных пользователем баллов | int |
| max_interaction_scores | Максимальное количество баллов за интерактивные вставки | int |
| pdf_viewed | Количество просмотренных материалов pdf в курсе | int |
| pdf_total | Общее количество pdf в курсе | int |
| link_viewed | Количество просмотренных материалов link в курсе | int |
| link_total | Общее количество link в курсе | int |
| html_viewed | Количество просмотренных материалов html в курсе | int |
| html_total | Общее количество html в курсе | int |
| scorm_total_time | Время прохождения материала scorm. Значение по умолчанию null | int / null |
| scorm_status | Статус прохождения материала scorm (completed, not completed, not started, Unknown, passed, failed) | string |
| scorm_percent | Процент прохождения материала scorm. Значение по умолчанию null | int / null |
| user_final_scores | Количество набранных баллов за финальный тест. Значение по умолчанию 0 | int |
| max_final_scores | Максимальное количество баллов за финальный тест. Значение по умолчанию 0 | int |
| percent_final_scores | Процент прохождения финального теста. Значение по умолчанию null | int / null |
| last_activity | Дата последней аквтиность пользователя. Формат Y-m-d\TH:i:sP (пример: 2020-12-01T15:52:01+03:00). Значение по умолчанию null. | string / null |
| current_turn | Номер текущей попытки прохождения финального теста. Значение по умолчанию null | int / null |
| turns_count | Количество попыток прохождения финального теста. Значение по умолчанию null | int / null |
| filled_type | Источник заполнения. Значение по умолчанию Польз. | string / null |
| group_region | Значение группы Регион | string |
| group_city | Значение группы Город | string / null |
| group_role | Значение группы Роль | string / null |
| group_position | Значение группы Должность | string / null |
| group_team | Значение группы Команда | string / null |
| group_department | Значение группы Подразделение | string / null |
| group_function | Значение группы Назначение | string / null |
| form_question_10 | Значение поля анкеты №10 | string / null |

Если в настройках компании отсутствуют анкеты, то полей вида form_question_x в структуре ответа не будет

### Пример
[Пример отчета](https://github.com/ekvio-dev/integration-api-response-examples/blob/master/examples/v2/training/trainings_statistic.json)