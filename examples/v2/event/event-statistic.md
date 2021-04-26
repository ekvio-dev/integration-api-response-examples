## Экспорт статистики по мероприятим
### Формат ответа
Отчет выгружается в формате **JSON**
### Структура ответа
| Атрибут |Описание| Типы значений |
| -------| ----- | ---- |
| event_id | ID мероприятия | int |
| event_status | Статус мероприятия (active, hide) | string |
| event_type | Тип мероприятия (offline, online, zoom) | string |
| login | Наименовение учетной записи | string |
| user_event_status | Статус участника мероприятия not enrolled, applied, approved, confirm attendance, participated, declined, missed) | string |
| created_at | Дата подачи заявки на участие в мероприятии. Формат значения Y-m-d\TH:i:sP (например, 2020-12-01T15:52:01+03:00) | string / null |
