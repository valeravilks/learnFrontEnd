# Ajax (XMLHttpRequest)

`XMLHttpRequest` – это встроенный в браузер объект, который даёт возможность делать HTTP-запросы к серверу без перезагрузки страницы.

Сейчас не обязательно использовать `XMLHttpRequest`, так как существует другой, более современный метод fetch.

В современной веб-разработке XMLHttpRequest используется по трём причинам:

* По историческим причинам: существует много кода, использующего XMLHttpRequest, который нужно поддерживать.
* Необходимость поддерживать старые браузеры и нежелание использовать полифилы (например, чтобы уменьшить количество кода).
* Потребность в функциональности, которую fetch пока что не может предоставить, к примеру, отслеживание прогресса отправки на сервер.

## Fetch

Современный способ отправки запросов на сервер с использованием промисов.

