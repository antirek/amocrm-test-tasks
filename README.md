# amocrm-test-tasks


### Тестовое задание 1: внешняя интеграция

1. Создать внешнюю интеграцию и получить accessToken

2. Сгенерировать 1200 сделок в amoCRM. У каждой сделки назначить бюджет сделки (price), величина которого случайна в диапазоне от 200 до 100000 рублей

3. Создать трех пользователей - менеджеров отдела продаж

4. Для сделок, бюджет которых свыше 10000 рублей, назначить ответственного менеджера отдела продаж, распределив сделки между менеджерами равномерно

5. Поставить ответственному менеджеру отдела продаж задачу на завтра - созвониться с клиентом

использовать nodejs, @mobilon-dev/amotop

видео: https://youtu.be/zRlO7e41bwg, https://youtu.be/CxQcB5AsyHI


### Тестовое задание 2: виджет ИНН

1. Создать виджет amoCRM для поиска реквизитов компании по ИНН в сервисе dadata и добавлении найденной компании в список компаний amoCRM
   
- В левом меню Настройки добавить страницу виджета с формой поиска компании по ИНН. 

- При нахождении компании отображать полученные реквизиты + кнопка "Добавить в amoCRM"
  
- По нажатию кнопки создавать компанию и заполнять доступные реквизиты

3. Виджет создать на основе widget-builder'а (пример https://gitlab.com/rocketsales/education/ivan-fokin, автообновление интерфейса)

4. Использовать API сервиса dadata (https://dadata.ru/api/find-party/)

