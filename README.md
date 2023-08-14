# Postman-newman
Простой и очень быстрый инструмент генерации и запуска тестов

простой пример того, что нужно сделать для проверки:
скачать Postman 
https://www.postman.com/downloads/

Скачать коллекцию запросов(всего для примера, но этого более чем достаточно) 
https://github.com/merc29/Postman-newman/blob/main/Norris%20joke.postman_collection.json

Установить Newman (работает поверх Node.js), как CLI-раннер тестов

npm install -g newman

из любой CLI с доступом к файлам запустить команду

newman run {{ПУТЬ ДО Norris joke.postman_collection.json}}
