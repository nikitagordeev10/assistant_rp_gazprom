# Проект: Ассистент руководителя проектов Газпрома (assistant_rp_gazprom)

Задача: Создать телеграм бота. В него загружается протокол совещаний в “.docx“ формате. Он анализирует данные по результатам еженедельного совещания, и формирует в ответном сообщении повестку и задачи со сроками и исполнителями. Формат ответа – майнд карта (в виде таблиц) - заголовок таблицы название проекта, а в таблице дата, задача, ответственный.

Создать телеграм бота - в него загружается протокол совещаний в “.docx“ формате. Он анализирует данные и формирует в ответном сообщении повестку и задачи со сроками и исполнителями. 
Формат ответа – майндкарта (таблицы). 
После загрузки отчёта руководителем ему на выбор доступны два варианта отчёта - или по проектам или по ответственным. Отображаемый руководителю отчёт по проекту в строке с задачей имеет статус выполнения (да/нет), возможность оставления комментария к задаче (прием текстового сообщения от участника) и добавление новой задачи. 
Ответственным отправляется таблица (с его задачами, сроками и проектом) в лс от бота после добавления файла руководителем.

Пример протокола
РЕШИЛИ:
В части Проекта КОММод:

1.	Обеспечить получение от АО «ВНИИГ» получение информации по срокам предоставления объемов демонтажа на основании данных по фундаменту, полученных от АО «УТЗ».
Ответственный: Д.В. Громак
Срок: 19.04.2024 (05.04.2024)

2.	Направить в адрес ООО «ВИЭ Инвест» данные по МОУ.
Ответственный: А.В. Константинов, В.В. Лисицкий
Срок: 19.04.2024 (05.04.2024)

3.	Направить в адрес ПАО «ТГК-1» комплект рабочей документации по тепловой изоляции турбоагрегата (изм.0).
Ответственный: Д.В. Громак
Срок: 15.04.2024 (31.03.2024)  

4.	Принять оформление внесенных в чертежи изменений в форме «облака».
Ответственный: Д.В. Громак
Срок: 	постоянно
