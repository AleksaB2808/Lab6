# Lab6
Функція task1

def task1(numbers):
    return sum(numbers)
Опис:

Вхідний параметр: numbers - список чисел.
Обчислює суму всіх чисел у списку numbers за допомогою вбудованої функції sum().
Повертає отриману суму.
Функція task2

def task2(tuple_of_elements):
    return len(tuple_of_elements)
Опис:

Вхідний параметр: tuple_of_elements - кортеж елементів.
Повертає довжину кортежу tuple_of_elements за допомогою функції len().
Функція task3

def task3(numbers_tuple):
    sorted_numbers = sorted(numbers_tuple, reverse=True)
    return sorted_numbers[0]
Опис:

Вхідний параметр: numbers_tuple - кортеж чисел.
Сортує числа у кортежі numbers_tuple у зворотньому порядку за допомогою вбудованої функції sorted() з параметром reverse=True.
Повертає перше (найбільше) число у відсортованому кортежі sorted_numbers.
Функція task4

def task4(dict_tuple):
    dictionary = dict_tuple[0]
    return dictionary.get("name", None)
Опис:

Вхідний параметр: dict_tuple - кортеж, що містить словник.
Отримує перший словник з кортежу dict_tuple.
Використовує метод .get() для отримання значення ключа "name" зі словника dictionary. Якщо ключ відсутній, повертає None.
Функція task5

def task5(list_of_tuples):
    sorted_tuples = sorted(list_of_tuples, key=lambda x: len(x[0]))
    return sorted_tuples[-1][-1]
Опис:

Вхідний параметр: list_of_tuples - список кортежів.
Сортує список list_of_tuples за довжиною першого елемента кожного кортежу за допомогою функції sorted() і параметра key=lambda x: len(x[0]).
Повертає останній елемент останнього кортежу у відсортованому списку sorted_tuples.
Функція task6

def task6(tuple_of_lists):
    odd_numbers = [num for sublist in tuple_of_lists for num in sublist if num % 2 != 0]
    product = 1
    for num in odd_numbers:
        product *= num
    return product
Опис:

Вхідний параметр: tuple_of_lists - кортеж списків чисел.
Створює список odd_numbers, який містить усі непарні числа з усіх списків, які містяться у tuple_of_lists.
Ініціалізує змінну product до 1.
Перемножує всі елементи списку odd_numbers, щоб отримати загальний добуток.
Повертає отриманий добуток.
Функція task7

def task7(tuple_of_tuples):
    return sum(second for first, second in tuple_of_tuples)
Опис:

Вхідний параметр: tuple_of_tuples - кортеж кортежів з двома елементами.
Сумує всі другі елементи (second) у кожному кортежі (first, second) з tuple_of_tuples.
Повертає отриману суму.







