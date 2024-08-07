<aside>
🚨 **Во всех задачах** используйте Poetry, пишите docstring, используйте аннотации типов, проверяйте код через Flake8 и mypy. Код размещайте в src/

</aside>

1. Написать функцию, которая получает на вход два списка чисел и возвращает новый список, содержащий только те числа, которые встречаются в обоих списках.
    
    **Пример ввода**:
    
    ```
    [1, 2, 3, 4], [3, 4, 5, 6]
    ```
    
    **Пример вывода**:
    
    ```
    [3, 4]
    ```
    
2. Написать функцию, которая получает на вход список чисел и возвращает новый список, содержащий только числа, которые являются палиндромами.
    
    **Пример ввода**:
    
    ```
    [121, 123, 131, 34543]
    ```
    
    **Пример вывода**:
    
    ```
    [121, 131, 34543]
    ```
    
3. Написать функцию, которая получает на вход два списка чисел и возвращает новый список, содержащий только те числа, которые есть только в одном из списков.
    
    **Пример ввода**:
    
    ```
    [1, 2, 3, 4], [3, 4, 5, 6]
    ```
    
    **Пример вывода**:
    
    ```
    [1, 2, 5, 6]
    ```
    
4. Исправьте код, содержащий ошибки PEP 8 и плохой нейминг. Добавьте docstring и аннотации типов. Flake8 и mypy не должны выдавать ошибок.
    
    ```python
    def circle_area(r: int) -> int:
        PI=3.14
        circleArea=PI * r**2
        return circleArea
    
    def format_description(r, area):
        return "Radius is " + str(r) + "; area is " + str(round(area, 2))
    
    def get_info(r: float):
        area = circle_area(r)
        description = format_description(r, area)
        print(description)
    
    radius=int(input("Enter circle radius (int): "))
    get_info(radius)
    ```
    
5. Создайте структуру проекта пакетом src/, виртуальное окружение, файл ,.gitignore разместите TXT-файл в папке data/, сделайте первый коммит.
    
    Ссылка на файл: [names.txt](https://drive.google.com/uc?export=download&id=1D3zM18IbfPL8Gg9Z0HFrsT0ED2upG3G3)
    
6. Напишите функцию, которая принимает имя файла и возвращает список имен, содержащихся в файле. Файл содержит имена на разных языках и может содержать знаки препинания вокруг имен, пустые строки и цифры. Функция должна удалить знаки препинания и цифры и возвращать только строки, содержащие имя. Сделайте новый коммит. В отдельном коммите измените TXT-файл, сделав его меньше для простоты тестирования.
7. Напишите другие функции, позволяющие из списка имен получать только русские и английские и записывать эти имена в файл в отсортированном виде. В итоге программа должна считывать данные из исходного файла и формировать два файла с русскими и английскими именами, отсортированными по алфавиту. Новые файлы должны создаваться в папке data/. Всегда делайте точечные коммиты. После завершения разработки сделайте отмену коммита, в котором был урезан исходный файл, т. е. верните полный TXT-файл.
8. Установите Flake8 и mypy. Проверьте ими ваш код. Если Flake8 выдает ошибки, устраните их с помощью инструмента black. Через git diff посмотрите, как black отформатировал ваш код. Добавьте аннотации типов. mypy не должен выдавать ошибки.
