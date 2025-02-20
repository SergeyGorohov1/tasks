[titanic.csv](https://drive.google.com/file/d/1Vxp1TfIiRF6t_KnuAqKDkJcnl_bdG0UQ/view)

1. Написать функцию, которая принимает на вход DataFrame из датасета "titanic.csv". Функция должна отфильтровать пассажиров, у которых цена билета больше 50 и возраст меньше 30 лет. Затем функция должна отсортировать отфильтрованный DataFrame по имени пассажира в алфавитном порядке и вернуть результат.
Ожидаемый результат: Отфильтрованный и отсортированный DataFrame.
2. Написать функцию, которая принимает на вход DataFrame из датасета "titanic.csv". Функция должна сгруппировать пассажиров по классу и посчитать среднюю стоимость билета и количество пассажиров в каждом классе. Функция должна вернуть результат в виде словаря в формате JSON.
    
    Пример JSON-файла:
    
    ```json
    {
        "1st": {
            "average_ticket_price": 84.15,
            "passenger_count": 216
        },
        "2nd": {
            "average_ticket_price": 20.66,
            "passenger_count": 184
        },
        "3rd": {
            "average_ticket_price": 13.68,
            "passenger_count": 491
        }
    }
    ```
    
3. Написать функцию, которая принимает на вход DataFrame из датасета "titanic.csv". Функция должна отфильтровать пассажиров, которые выжили в катастрофе, и записать данные об этих пассажирах в файл в формате JSON. Функция должна вернуть количество выживших пассажиров.
    
    Пример JSON-файла:
    
    ```json
    [
        {
            "survived": 1,
            "pclass": 1,
            "name": "Allen, Miss. Elisabeth Walton",
            "sex": "female",
            "age": 29.0,
            "sibsp": 0,
            "parch": 0,
            "ticket": "24160",
            "fare": 211.3375,
            "cabin": "B5",
            "embarked": "S"
        },
        {
            "survived": 1,
            "pclass": 1,
            "name": "Allison, Master. Hudson Trevor",
            "sex": "male",
            "age": 0.92,
            "sibsp": 1,
            "parch": 2,
            "ticket": "113781",
            "fare": 151.55,
            "cabin": "C22 C26",
            "embarked": "S"
        },
        ...
    ]
    ```
    

4. Создайте строку с текстом, включающим имена Twitter аккаунтов (например, "@user1, @user2, @user3"). Напишите регулярное выражение для поиска и извлечения всех Twitter имен.

```python
import re

# Создание строки с текстом
text_data = "Проверьте новые обновления от @user1 и @user2. Расскажите друзьям: @user3 тоже приглашен!"
```

5. Создайте строку с текстом, включающим URL-адреса (например, "Посетите наш сайт: [https://www.example.com](https://www.example.com/)"). Напишите регулярное выражение для поиска и извлечения всех URL-адресов.

```python
import re

# Создание строки с текстом
text_data = "Посетите наш сайт: <https://www.example.com>. Также, проверьте новости по адресу: <http://news.example.org>."
```

1. Создайте строку с текстом, содержащим коды товаров (например, "Код товара: 123456789"). Напишите регулярное выражение для поиска и извлечения всех кодов товаров.

```python
import re

# Создание строки с текстом
text_data = "Код товара: 123456789. Другой товар: 987654321."
```

1. Создайте строку с текстом, включающим IP-адреса (например, "Сервер: 192.168.1.1"). Напишите регулярное выражение для поиска и извлечения всех IP-адресов.

```python
import re

# Создание строки с текстом
text_data = "Сервер: 192.168.1.1, Клиент: 10.0.0.1"
```

1. Создайте строку с текстом, включающим MAC-адреса (например, "Устройство: 00:1A:2B:3C:4D:5E"). Напишите регулярное выражение для поиска и извлечения всех MAC-адресов.

```python
import re

# Создание строки с текстом
text_data = "Устройство: 00:1A:2B:3C:4D:5E, Другое устройство: 11:22:33:44:55:66"
```

