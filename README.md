Проект №0 — Registration/Authorization form testing

Здравствуйте, дорогие друзья! Поздравляем: вы в самом начале важного и увлекательного пути. Этот путь состоит из одиннадцати ступеней мастерства. Для продвижения по ступеням вам нужно будет прокачивать навыки: получать знания и закреплять их на практике. Сфера ИТ для вас новая, и иногда может показаться, что ничего не понятно. Это нормально (и не только для ИТ-сферы). Справиться с любой сложностью поможет корректно составленный вопрос. В каждой непонятной ситуации формулируйте вопрос. Как только удалось сформировать правильный вопрос, считайте, что полдела сделано. С этим вопросом отправляйтесь (в порядке приоритета):

    в поисковик,
    к одногруппнику / другу / в общий чат группы.

Главное — в курсе нет ничего, что вам не под силу. Не будем терять времени, давайте приступим к практике. Можете использовать любые источники: блоги, страницы сообществ по тестированию, youtube, habr, ru.stackoverflow и любые учебные ресурсы.

Поехали!

p.s. в разделе projects → video вы найдёте обучающие ролики, часть из них вам пока не понадобится. Мы собрали две основные подборки: обязательные ролики и очень рекомендованные к просмотру. Просмотр остальных — по желанию.
Contents

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

    Пожалуйста, оставьте обратную связь по проекту в форме обратной связи.
