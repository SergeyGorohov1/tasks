**Задача 1**

У вас есть строка 

```python
line = "13f et3 5kk 54"
```

Выведите, сколько чисел в строке и сколько букв. 

```python
Всего чисел: 6
Всего букв: 5
```

**Задача 2**

 У вас есть строка, посчитайте, какой процент от нее составляют пробелы

```python
line = "13f et3 5kk54"
```

Пример вывода:

```python
Пробелов: 2, это 40%
```

**Задача 3**

У вас есть строка, посчитайте количество заглавных букв в ней. Проверить, является ли буква заглавной можно с помощью `.isupper()`

```python
line = "A13f et3 D 5kk54 M"
```

```python
Заглавных букв: 3
```

**Задача 4**

У вас есть строка. 

```python
line = "abcdefghijklmnopqrstuvwxyz"
```

Со стандартного ввода одной строкой подаются два числа x и y, разделенные дефисом.

```python
1-4
```

Разделите строку с помощью среза и верните буквы в соответствующем интервале (от x до y) ***ВКЛЮЧИТЕЛЬНО***. Пример вывода

```python
bcde
```

**Задача 5**

Со стандартного ввода поступает фраза, посчитайте, сколько раз в ней встречается буква “р”. Выведите ответ числом.

**Задача 6**

Попросите пользователя ввести строку. Затем запросите подстроку. Используйте оператор `in`, чтобы проверить, содержится ли введенная подстрока в введенной строке. Выведите результат.

**Задача 7**

Есть строка с текстом. 

```python
text = "Python is awesome language for start your IT career"
vowels = "aeiouAEIOU"
```

Используйте цикл и оператор `in`, чтобы проверить, содержатся ли каждая из гласных букв в строке. Выведите гласные буквы, которые есть в слове. 

**Задача 8**

Вам дана строка с предложением. Запросите пользователя ввести слово. 

```python
sentence = "Python - лучший язык программирования в мире потому что он легкий и понятный для изучения"
```

Используйте оператор `not in`, чтобы проверить, не содержится ли введенное слово в предложении. Выведите результат.

**Задача 9**

Вам дана строка. 

```python
text_to_search = "В этом отрывке известного романа описывается ключевой момент в жизни главного героя."
```

Запросите пользователя ввести подстроку для поиска. Используйте метод `find`, чтобы найти индекс первого вхождения подстроки в строку. Выведите результат.

Пример вывода:

```python
Подстрока 'отрыв' найдена в позиции 4.
*ИЛИ*
Подстрока 'тест' не найдена в тексте.
```

**Задача 10**

Вам дана строка. 

```python
text_to_count = "Статья рассказывает о последних научных открытиях в области исследования космоса. Интересно, что исследователи утверждают, что космическое время может быть относительным."
```

Запросите пользователя ввести слово для подсчета вхождений. Используйте цикл и метод `find`, чтобы посчитать количество вхождений слова в тексте. Выведите результат.

Пример вывода:

```python
Слово 'статья' встречается в тексте 4 раз(а).
```

**Задача 11**

Вам дана строка. 

```python
news_article = "В последней новостной статье рассказывается о событиях в мире политики и экономики."
```

Запросите пользователя ввести слово для подсчета его вхождений в текст. Используйте метод `count`, чтобы подсчитать количество вхождений слова в текст. Выведите результат.

**Задание 12**

Вам дана строка. 

```python
sentence = "ЭТО пример Текста с РАЗНЫМИ Регистрами букв."
```

Преобразуйте все символы в нижний регистр. Выведите результат.

**Задача 13**

Вам дана строка с заголовком новой книги. 

```python
book_title = "путешествие в неизведанные миры"
```

Преобразуйте все символы в верхний регистр. Выведите результат.

**Задача 14**

Вам дана строка. 

```python
movie_scene = "В этой сцене герой произносит знаменитую фразу: 'Я всегда с вами'."
```

Запросите пользователя ввести подстроку для замены. Запросите пользователя ввести новую подстроку. Замените первое вхождение подстроки новой подстрокой. Выведите результат.

**Задача 15**

Вам дано предложение. 

```python
sentence = "Это пример использования метода split в Python."
```

Разделите предложение на слова. Выведите список слов.

**Задача 16**

Есть список слов. 

```python
word_list = ["Это", "пример", "использования", "метода", "join", "в", "Python."]
```

Объедините слова в предложение. Выведите получившееся предложение.

**Задача 17**

Вам дана строка с датой 

```python
date_string = "2023-12-19"
```

Получите отдельные компоненты даты (год, месяц, день). Выведите полученные компоненты.

Пример вывода:
Год: 2023, Месяц: 12, День: 19