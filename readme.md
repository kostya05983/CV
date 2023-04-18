[![ru](https://img.shields.io/badge/lang-ru-red.svg)](https://github.com/kostya05983/CV/blob/main/readme-ru.md)
[![en](https://img.shields.io/badge/lang-en-blue.svg)](https://github.com/kostya05983/CV/blob/main/readme.md)

### Now
I'm head of the cluster of java backenders in the direction of real estate in Kontur. Also, I'm Techlead in "Контур.Приёмка" product. 

### Education
Bachelor's degree of information technology in NSTU 2016-2020.

### Foreign languages
English B2

Deutch A1

###Native language
Russian

### Extra activites in IT
* I have made some of internship tasks for c# [2020 г](https://ulearn.me/Course/backend-internship-2020/Refaktoring_4d4966b2-144f-4244-830c-0c81173e87cb), [2021 г](https://ulearn.me/Course/backend-internship-2021/Umnyy_kholodil_nik_5a4a5b9b-2b56-444a-9275-520bd4eb1c4b), [2022 г](https://ulearn.me/Course/backend-internship-2022/Avtokomplit_7c31b316-d9d5-4dfa-8cc4-5ebe806821d6)

* I have teached the database course students of URFU since 2022

* I have intervied developers in Kontur since 2021

* I have perfomed in [SnowOne 2021](https://www.youtube.com/watch?list=PLecWId-JT7S5cqUiY7ixWcZgjdRV4upnw&time_continue=1&v=lHX9iRb9184&feature=emb_logo&ab_channel=JUGNsk), [meetup JUG.EKB](https://www.youtube.com/watch?v=yePWmqo4qFU&ab_channel=JUG.EKB), [meetup Backend Update 2022](https://eventskbkontur.timepad.ru/event/2169073/)

### Expirience

|Position| Stack of technology | Time|
|------|------|------|
|Middle| kotlin\java, spring, vaading, clickhouse, vertx, mongodb, mysql, hazelcast, swing ui, docker | 01.07.2018 - 07.08.2019|
| Junior | kotlin, spring, rabbitmq, mongodb, nginx, elastic, k8s, grafana, graphite, moira | 13.08.2019-01.04.2020 |
| Middle | kotlin, spring, rabbitmq, mongodb, nginx, elastic, k8s, grafana, graphite, moira | 01.04.2020-01.01.2021 |
| Senior | kotlin, spring, rabbitmq, mongodb, nginx, elastic, k8s, grafana, graphite, moira | 01.01.2021-03.09.2021 |
| Lead | kotlin, spring, rabbitmq, mongodb, nginx, elastic, k8s, grafana, graphite, moira | 03.09.2021-настоящее время |

### Solved tasks
Below, you can see different tasks with 2 and more months cost

|Goal |Result| Is it proactivity? | Year | Waste time |
| -------| ---------| -------| ----| ----|
| Design API for product "Контур.Приёмка". Full version of products includes two applications one is for b2b client and another if for b2c client and telegram bot | First part of design we made with another lead, but than I continued to design only by myself. I used DDD aproach in this product. | No | 2022г | 4 месяца+наст_время |
| Design and realization of MVP product "Контур.Приёмка" | I designed MVP with another lead, we used DDD aproach. MVP is used by different clients | No |2022г| 2 months |
| Мониторить объекты недвижимости, если произошли изменения, необходимо автоматически заказать выписки и предоставить клиенту | Мной было спроектирован модуль в [API](https://reestro-docs.kontur.ru/realty-api/monitoring/process.html), задачу реализовывали 2 стажера, я довёл задачу до конца. | Нет | 2022г | 3 месяца |
| Рассылать уведомления о продлении, если у клиента на счёте было денег меньше определённого процента | Был реализован демон, который мог пройтись по всем услугам b2b организации и высчитать проценты, а затем разослать письма админка b2b организации. | Нет| 2022г | 2 месяца |
| Выгрузка списка сделок в Excel | Мной было выполнена постановка и проектирование, реализацию делал другой разработчик.  | Нет | 2021г | 1 месяц|
| Модуль Закладные Веб Апи | Мной был спроектирована веб часть модуля закладные и реализована интеграция с [транспортой частью](https://reestro-docs.kontur.ru/realty-api/mortgage/mortgage.html), в реализации также был задействован другой разработчик, он делал часть с просчётом статусов черновика. | Нет | 2021г | 5 месяцев |
| Интеграция с банком Тинькофф для ДКП | Для продукта Реестро модуля сделки была спроектирована мной и написана мной и ещё одним разработчиком интеграция с Тинькофф | Нет | 2021г | 6 месяцев |
| Фильтрация сделок в списке по параметрам | Реализацию осуществлял другой разработчик(не лид). Затем как ушёл лид, пришлось взять инициативу на себя и доводить задачу до состояния продакшена. | Нет | 2020г | 3 месяца |
| Мультисделка. Возможность в пределах одного черновика сделки, отправлять несколько сделок. | Проектировали совместно с Лидом. Затем он ушёл, задачу доводил сам. | Нет | 2020г | 3 месяца |
| Перенести сервис пользователей, организаций, представителей с node-js на kotlin. | Перенос был осуществлён с 0 down time-ом. | Нет | 2020г | 6 месяцев|
| Сделать Веб Апи для выписок, две версии по версии для каждого продукта Контур.Реестро и Контур.Панорама | Был написан сервис взаимодействующий с [транспортной системой Реестро](https://reestro-docs.kontur.ru/realty-api/methods/create-docflow.html)| Нет | 2020г | 3 месяца |
|Запускать приложение в IDE по кнопке play. (Надоело подкладывать файлик с настройками) | Написал библиотеку, которая при старте сама генерирует и подкладывает нужные настройки в spring environment. | Да | 2019г | 1 месяц | 
|Написать сервис для продукта, чтобы отправлять нотификации через инфраструктуру Контура, учесть наши бизнес потребности. | Сервис работает с 2019 года, очень маленькие затраты на поддержку. | Нет | 2019г | 2 месяца |
