# Проект guess-number-check. Угадай число

## Оглавление  
[1. Описание проекта](https://github.com/kridiner/sf_data_science/blob/main/guess-number-task/README.md#Описание-проекта)  
[2. Какой кейс решаем?](https://github.com/kridiner/sf_data_science/blob/main/guess-number-task/README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](https://github.com/kridiner/sf_data_science/blob/main/guess-number-task/README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/kridiner/sf_data_science/blob/main/guess-number-task/README.md#Этапы-работы-над-проектом)  
[5. Результат](https://github.com/kridiner/sf_data_science/blob/main/guess-number-task/README.md#Результат)    
[6. Выводы](https://github.com/kridiner/sf_data_science/blob/main/guess-number-task/README.md#Выводы) 

### Описание проекта    
Угадать загаданное компьютером число за минимальное число попыток.

:arrow_up:[к оглавлению](https://github.com/kridiner/sf_data_science/blob/main/guess-number-task/README.md#Оглавление)


### Какой кейс решаем?    
Нужно написать программу, которая угадывает число за минимальное число попыток

**Условия соревнования:**  
- Компьютер загадывает целое число от 1 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений

**Что практикуем**     
Учимся писать хороший код на python

:arrow_up:[к оглавлению](https://github.com/kridiner/sf_data_science/blob/main/guess-number-task/README.md#Оглавление)

### Краткая информация о данных
Работаем с целыми числами от 1 до 100. Используем генерацию случайных чисел из numpy. 
  
:arrow_up:[к оглавлению](https://github.com/kridiner/sf_data_science/blob/main/guess-number-task/README.md#Оглавление)


### Этапы работы над проектом  
- Первый файл с кодом game.py содержит код с программой, которая загадывает число, а пользователь отгадывает. Программа даёт подсказки о попытке, больше ли загаданное число, или меньше.
- Файл game_v2.py содержит основную программу - две функции: random_predict - угадывающая число (перебирающая число-догадку), возвращающая количество итераций отгадывания, и score_game - загадывающая 1000 чисел и вызывающая random_predict для отгадывания каждого, собирая количество попыток в массив. После чего вычисляет и выводит на экран среднее число попыток (среднее по полученному массиву), используя библиотечную mean из numpy.


:arrow_up:[к оглавлению](https://github.com/kridiner/sf_data_science/blob/main/guess-number-task/README.md#Оглавление)


### Результат:  
....

:arrow_up:[к оглавлению](https://github.com/kridiner/sf_data_science/blob/main/guess-number-task/README.md#Оглавление)


### Выводы:  
....

:arrow_up:[к оглавлению](https://github.com/kridiner/sf_data_science/blob/main/guess-number-task/README.md#Оглавление)
