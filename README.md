#Домашнее задание 
Задача касается разработки LMS-системы,
в которой каждый желающий может размещать
свои полезные материалы или курсы.

Ранее в проектах мы могли сразу видеть
визуальное отображение результата разработки,
теперь работа будет над SPA-приложением и 
результатом создания проекта будет бэкенд-сервер, 
который возвращает клиенту JSON-структуры.

Завести группу модераторов и описать для
нее права работы с любыми уроками или курсами,
но без возможности их удалять и создавать новые.
Заложите функционал такой проверки в контроллеры.

Для сохранения уроков и курсов реализщвана дополнительная
проверка на отсутствие в материалах ссылок на сторонние ресурсы,
кроме youtube.com.

Добавлена модель подписки на обновления курса для пользователя.

Реализован эндпоинт для установки подписки пользователя
и на удаление подписки у пользователя.

Реализована пагинаця для вывода всех уроков и курсов.

Написаны тесты, которые будут проверять корректность работы
CRUD уроков и функционал работы подписки на обновления курса.

Сохраните результат проверки покрытия тестами.

Подключить и настроить вывод документации для проекта.
Убедиться, что каждый из реализованных эндпоинтов описан
в документации верно, при необходимости описать вручную.

Подключить возможность оплаты курсов через https://stripe.com/docs/api.

Доступы можно получить напрямую из документации, а также пройти простую регистрацию по адресу https://dashboard.stripe.com/register.

Для работы с запросами вам понадобится реализовать обращение к эндпоинтам:

https://stripe.com/docs/api/payment_intents/create — создание платежа;
https://stripe.com/docs/api/payment_intents/retrieve — получение платежа.
Для тестирования можно использовать номера карт из документации:

https://stripe.com/docs/terminal/references/testing#standard-test-cards