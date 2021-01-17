
# Тестирование API

Код и примеры для тестов по API

1) Argraprse, аргументы в pytest
2) requests
3) Параметризация фикстур
4) Тестирование API

1. Тестирование REST API сервиса: https://dog.ceo/dog-api/.
2. Тестирование REST API сервиса: https://www.openbrewerydb.org/.
3. Тестирование REST API сервиса: https://jsonplaceholder.typicode.com/.
4. В отдельном модуле (файле) тестовая функция  принимаем 2 параметра:
url - должно быть значение по умолчанию https://ya.ru
status_code - значение по умолчанию 200
Параметры реализованы через pytest.addoption.
Фикcтура и тестовая функция размещены в одом файле.
