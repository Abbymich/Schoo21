Проект №0 — Registration/Authorization form testing

Hands-on web-service testing

Создание тест-кейсов при отсутствии бизнес-аналитики и технических требований
Функциональное тестирование формы регистрации и авторизации веб-сервиса

Chapter I
1.1. Registration form 1.2. Task 1
Chapter II
2.1. Authorization form 2.2. Task 2

Instructions

Все созданные файлы и отчеты загружайте в папку src ветка develop.

Созданные документы могут быть в любом формате, но лучше всего использовать Notion и выгружать документы в формате pdf.

Документы должны быть читаемы, не поломаны, должны открываться без пароля.
Chapter I
Registration form

На сайте СберМаркет https://sbermarket.ru/ есть форма для регистрации/авторизации.

WEB

Подобная форма есть во всех приложениях и веб-сервисах. Рассмотрим ситуацию, когда нет никакой документации (требований и технического задания) к данной форме. При тестировании опирайтесь на здравый смысл и, конечно, интернет. blush

Точно известно, что с помощью этой формы пользователь должен иметь возможность зарегистрироваться с помощью мобильного номера, учетной записи VK или mail.ru.
Task 1

    Создайте документ «Registration_form». В документе перечислите и опишите все поля и элементы этой формы. Например: текстовое поля для ввода «Номер телефона», кнопка «Получить код в СМС»;
    создайте документ «Registration_test». Добавьте в документ 5 тестовых сценариев регистрации.

Пример оформления тестового сценария:

WEB

    Протестируйте форму регистрации по созданным сценариям. Всё ли работает корректно, как описано в тестовых сценариях? Перед каждым сценарием добавьте строчку «Пройден успешно» или «Не пройден. Найдена ошибка: <описание ошибки>».

Chapter II
Authorization form

После успешной регистрации пользователь должен иметь возможность авторизоваться.
Task 2

    Создайте документ «Authorization_test». Добавьте в документ 5 тестовых сценариев авторизации;
    протестируйте форму авторизации по созданным сценариям. Всё ли работает корректно, как описано в тестовых сценариях? Перед каждым сценарием добавьте строчку «Пройден успешно» или «Не пройден. Найдена ошибка: <описание ошибки>».

Double-check

Перед загрузкой выполненного проекта в репозиторий перепроверьте наличие всех необходимых файлов, которые требовалось создать во время выполнения проекта:

    файлы:
        «Registration_form»;
        «Registration_test»;
        «Authorization_test».
 
