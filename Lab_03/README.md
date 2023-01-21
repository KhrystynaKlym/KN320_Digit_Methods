# Звіт до лабораторної роботи №3
## Тема: Операції над масивами даних
### Мета роботи: Навчитись виконувати операції над масивами даних.
---
## **Виконання роботи**

***- Результати виконання завдань:***


## **Операції над масивами**

Хоча базово всі дані інтерпретуються як масиви, можна працювати з двовимірними масивами як з алгебраїчними матрицями.

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_1.jpg "Визначення")
________________________


Згенеруємо декілька масивів різними способами та виконаємо базові математичні операції.

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_2.jpg "Результат")


![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_3.jpg "Результат")
____
## **!!! >>>HOMEWORK<<< !!!**
- створила власну матрицю A за допомогою методу `eye`(створює одиничну діагональну матрицю);
- виконала порівняння елементів матриці А на наявність 1;
- створила матрицю В за допомогою методу `ones`(матриця, всі елементи якої рівні 1);
- знайшла різницю матриць В-А (у результаті вийде матриця, де центральна діагональ все нулі

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_4.jpg "Результат")


## **Множення матриць**

Якщо масив явно не задати як матрицю, тоді операції будуть виконуавтись над кожним елементом.

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_5.jpg "Результат")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_6.jpg "Результат")
_____

## **Вирівнювання розмірностей**

`broadcasting` - механізм який дозволяє вирівняти розмірність масивів для того, щоб здійснити операцію над кожним його елементом. Масиви повинні бути співрозмірні, або один з вимірівв має бути 1 (рядок або стопець).

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_7.jpg "Результат")
______

## **Конкатенація, повторення та зміна форми (shape)**

- конкатенація (`concatenate`) - процес зчеплення двох і більше елементів (рядків, стовпців), у нашому випадку масивів які мають однакову форму shape;

- повторення (`tile`) - процес побудови масива шляхом повторення заданого елемента;

- зміна форми (`reshape`) або розмірності масива за умови що сумарна розмірність залишиться незмінною;

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_8.jpg "Результат")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_9.jpg "Результат")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_10.jpg "Результат")
_____

## **!!! >>>HOMEWORK<<< !!!**

- Створила за допомогою `arange` двохвимірний масив `а` розмірністю 3х3 та виконала конкатенацію і повторення.
- Створила за допомогою `arange` масив `b` розмірністю 3х2 (кількість рядків та стовпців різна).  Оскільки, розмірність масивів `а`(3x3) і `b`(3x2) різна, то щоб виконати конкатенацію таких масивів, змінила розмірність масиву `b`. 

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_11.jpg "Результат")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_12.jpg "Результат")


- Створила двовимірний масив `c` (розмірністю 1х12) та знайшла всі можливі комбінації reshape.

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_13.jpg "Результат")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_14.jpg "Результат")
_____

## **Трансформації масивів**
- масиви можуть бути трансформовані багатьма способами, зміщуючи позиції рядків або стопців;
- транспонація - заміна рядків на стопці;
- функції `size` та `shape` - дозволяють визначити кількість елементів

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_15.jpg "Результат")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_16.jpg "Результат")

___
## **!!! >>>HOMEWORK<<< !!!**
- створила вектор з 12 елементів, визначила його `shape`, `size` та `ndim`;
- змінила розмірніть, перетворивши вектор у матрицю;
- здійснила транспонування отриманої матриці та обернула її;
- Перетворила отриманий багатовимірний масив назад у вектор (стрічку)

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_17.jpg "Результат")

![alt text](https://github.com/KhrystynaKlym/KN320_Digit_Methods/raw/main/Lab_03/Screenshots/Screenshot_18.jpg "Результат")
        
______
______
_____
  
### ***Висновок:***

- навчилася виконувати оператції над масивами :heavy_check_mark:
- попрактикувалася у множенні матриць :heavy_check_mark:
- ознайомилася із вирівнюванням розмірностей :heavy_check_mark:
- навчилася виконувати конкатенацію, повторення та зміну форми (shape) :heavy_check_mark:
- попрактикувалася у трансформації масивів :heavy_check_mark:
- дала відповіді на поставлені завдання :heavy_check_mark:
- роботу оформила. Все гуд :heavy_check_mark:
- все вдалося, всі завдання виконані :heavy_check_mark:
- завдяки Вашому детальному поясненню жодних складностей не виникло :ok_hand:
- так, подобається; це зручний формат здачі роботи :thumbsup:
- поки що побажань нема, все ГУД :smiley:
---