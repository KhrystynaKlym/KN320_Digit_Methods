# Звіт до лабораторної роботи №1
## Тема: Робота з бібліотекою numpy
### Мета роботи: Навчитись працювати з бібліотекою numpy.
---
## **Виконання роботи**

***- Результати виконання завдань:***


### Встановлення бібліотеки `NumPy`
 Для початку встановлюю бібліотеку `NumPy`. Дана команда виконується у командній стрічці (потрібно мати встановлений Python та `pip`).
```bash
pip install numpy 
```
Як видно на скріні нижче, бібліотека `numpy` вже інстальована. Система пропонує оновити версію `pip` з версії 22.2.2 до 22.3.1. Оновимо `pip`.

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/2.jpg "Оновлення `pip`")

 Дана бібліотека дозволяє працювати з різними типами даних ("Numeric Python" - числовими), спрощуючи їх використання визначене у класичному Python, додає можливість працювати з векторами та матрицями. 
Для роботи з бібліотекою будемо працювати інтерактивно в Jupytere Notebook.

Для цього: 
- створила файл `numpy.ipynb`; 
- всі файли розмістила в репозиторії Github.

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/1.jpg "`numpy.ipynb`")

_______
1. Задано список температур:
    ```python
        import numpy as np
        temperature = [20.1, 20.1, 20.2, 20.4]
        print(temperature)
    ```
## **Робота з простими лістами:**


![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/3.jpg "Результат обчислень")

### **~HOMEWORK~**

Отже, множення неуспішне((( В результаті отримали новий список температур `t1`, кількість елементів якого збільшена в 5 разів порівняно з початковим `t1=temperature*5`

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/4.jpg "Результат обчислень")


### **~HOMEWORK~**

Отже, множення успішне! В результаті отримали новий список температур `t1`, кожен елемент якого помножений на 5 та збільшений на 30 `t1=temperature*5`

## **Робота з лістами в бібліотеці `numpy`:**
![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/5.jpg "Результат обчислень")
________

## **Вектори, створення та робота з ними**

```python
l1=[1, 2, 3, 4, 5]
l2=[6, 7, 8, 9, 10]
l3=[11, 12, 13, 14, 15]
vector_1=np.array(l1)
vector_2=np.array([l1, l2])
vector_3=np.array([l1, l2, l3])
vector_4=np.array([[l1, l2, l3], [l1, l2, l3], [l1, l2, l3], [l1, l2, l3]])

print(f"Це є list: {l1}\n\n Масив numpy `vector_1`: {vector_1} \n\n Масив numpy `vector_2`:\n {vector_2} \n\n Масив numpy `vector_3`:\n {vector_3} \n\n Масив numpy `vector_4`:\n {vector_4}")

t1=vector_1*7
t2=vector_2*7
t4=vector_4*7
print(f"\nРезультат множення елементів масиву 'vector_1' на 7: {t1}, \n Результат множення масиву 'vector_2' на 7: {t2}, \n Результат множення масиву 'vector_4' на 7: {t4}")
```

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/6.jpg "Результат обчислень")
![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/7.jpg "Результат обчислень")
![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/8.jpg "Результат обчислень")

## **Метод arange - генерує послідовність чисел з певним кроком у заданому інтервалі**

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_9.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_10.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_11.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_12.jpg "Результати")


## **Метод linspace - генерує задану кількістю чисел у певному діапазоні, 50 чисел за замовчуванням**

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_13.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_14.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_15.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_16.jpg "Результати")


## **Типи масивів/векторів, багатовимірні масиви, розуміння вимірів**

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_17.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_18.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_19.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_20.jpg "Результати")

## **Indexing and Slicing**

***Indexing*** - використовується для доступу до елементів масиву.

***Slicing*** - використовується для доступу до декількох елементів зразу.

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_21.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_22.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_23.jpg "Результати")


Для доступу до декількох елементів використовують Slicing.

Принцип доступу до елементів  `S[start:stop:step]`. Елемент `stop` не включається у вивід.

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_24.jpg "Результати")

Такий самий принцип Slicing може використовуватись для багатовимірних масивів.

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_25.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_26.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_27.jpg "Результати")

Slicing дозволяє брати не тільки послідовні значення але із заданим кроком.

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_28.jpg "Результати")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_29.jpg "Результати")

Можна здійснювати вибірку елементів по умові

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_30.jpg "Результати")

## **Функції для створення матриць: ones, zeros, identity, eye, empty**

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_01/Screenshots/Screenshot_31.jpg "Результати")


    

            
        
______
______
_____
  
### ***Висновок:***

- втсановила бібліотеку `numpy` :heavy_check_mark:
- навчилася створювати вектори та працювати з ними :heavy_check_mark:
- попрацювала з методами `arange` та `linspace` :heavy_check_mark:
- ознайомилася із типами масивів/векторів :heavy_check_mark:
- ознайомилася із багатовимірними масивами та зрозуміла їхню вимірність :heavy_check_mark:
- попрацювала із `Indexing` та `Slicing` :heavy_check_mark:
- ознайомилася із функціями для створення матриць: `ones`, `zeros`, `identity`, `eye`, `empty` :heavy_check_mark:
- дала відповіді на поставлені завдання :heavy_check_mark:
- роботу оформила. Все гуд :heavy_check_mark:
- все вдалося, всі завдання виконані :heavy_check_mark:
- завдяки Вашому детальному поясненню жодних складностей не виникло :ok_hand:
- так, подобається; це зручний формат здачі роботи :thumbsup:
- поки що побажань нема, все ГУД :smiley:
---