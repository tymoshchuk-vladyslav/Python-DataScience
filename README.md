# Домашнє завдання - 1.

### Файл - Hw1.ipynb

1. Створіть одновимірний масив (вектор) з першими 10-ма натуральними числами та виведіть його значення.

2. Створіть двовимірний масив (матрицю) розміром 3x3, заповніть його нулями та виведіть його значення.

3. Створіть масив розміром 5x5, заповніть його випадковими цілими числами в діапазоні від 1 до 10 та виведіть його значення.

4. Створіть масив розміром 4x4, заповніть його випадковими дійсними числами в діапазоні від 0 до 1 та виведіть його значення.

5. Створіть два одновимірних масиви розміром 5, заповніть їх випадковими цілими числами в діапазоні від 1 до 10 та виконайте на них поелементні операції додавання, віднімання та множення.

6. Створіть два вектори розміром 7, заповніть довільними числами та знайдіть їх скалярний добуток.

7. Створіть дві матриці розміром 2x2 та 2x3, заповніть їх випадковими цілими числами в діапазоні від 1 до 10 та перемножте їх між собою.

8. Створіть матрицю розміром 3x3, заповніть її випадковими цілими числами в діапазоні від 1 до 10 та знайдіть її обернену матрицю.

9. Створіть матрицю розміром 4x4, заповніть її випадковими дійсними числами в діапазоні від 0 до 1 та транспонуйте її.

10. Створіть матрицю розміром 3x4 та вектор розміром 4, заповніть їх випадковими цілими числами в діапазоні від 1 до 10 та перемножте матрицю на вектор.

11. Створіть матрицю розміром 2x3 та вектор розміром 3, заповніть їх випадковими дійсними числами в діапазоні від 0 до 1 та перемножте матрицю на вектор.

12. Створіть дві матриці розміром 2x2, заповніть їх випадковими цілими числами в діапазоні від 1 до 10 та виконайте їхнє поелементне множення.

13. Створіть дві матриці розміром 2x2, заповніть їх випадковими цілими числами в діапазоні від 1 до 10 та знайдіть їх добуток.

14. Створіть матрицю розміром 5x5, заповніть її випадковими цілими числами в діапазоні від 1 до 100 та знайдіть суму елементів матриці.

15. Створіть дві матриці розміром 4x4, заповніть їх випадковими цілими числами в діапазоні від 1 до 10 та знайдіть їхню різницю.

16. Створіть матрицю розміром 3x3, заповніть її випадковими дійсними числами в діапазоні від 0 до 1 та знайдіть вектор-стовпчик, що містить суму елементів кожного рядка матриці.

17. Створіть матрицю розміром 3x4 з довільними цілими числами і створінь матрицю з квадратами цих чисел.

18. Створіть вектор розміром 4, заповніть його випадковими цілими числами в діапазоні від 1 до 50 та знайдіть вектор з квадратними коренями цих чисел.

Домашня робота здається у вигляді Jupyter файлу Hw1.ipynb.


# Домашнє завдання - 2

### Файл - Hw2.1.ipynb

Не турбуйтеся, якщо у вас не буде все одразу виходити. Робота будь-якого дата саєнтіста тісно пов'язана з пошуком та дослідженнями, тому дуже важливо навчитися шукати потрібну інформацію та адаптувати її під свої потреби. Також, з будь-якими питаннями ви можете звертатися до ментора.

### Частина перша: Знайомство з Pandas.
Прочитайте дані за допомогою методу read_html з таблиці "Коефіцієнт народжуваності в регіонах України (1950—2019)" посилання

#### Необхідно виконати:

Вивести перші рядки таблиці за допомогою методу head
Визначте кількість рядків та стовпців у датафреймі (атрибут shape)
Замініть у таблиці значення "—" на значення NaN
Визначте типи всіх стовпців за допомогою dataframe.dtypes
Замініть типи нечислових колонок на числові. Підказка - це колонки, де знаходився символ "—"
Порахуйте, яка частка пропусків міститься в кожній колонці (використовуйте методи isnull та sum)
Видаліть з таблиці дані по всій країні, останній рядок таблиці
Замініть відсутні дані в стовпцях середніми значеннями цих стовпців (метод fillna)
Отримайте список регіонів, де рівень народжуваності у 2019 році був вищим за середній по Україні
У якому регіоні була найвища народжуваність у 2014 році?
Побудуйте стовпчикову діаграму народжуваності по регіонах у 2019 році
Робота здається у вигляді Jupyter файлу Hw2.1.ipynb

### Частина друга: Аналіз файлів
Проведіть аналіз файлу 2017_jun_final.csv. Файл містить результати опитування розробників у червні 2017 року.

#### Необхідно виконати:

Прочитайте файл 2017_jun_final.csv за допомогою методу read_csv
Прочитайте отриману таблицю, використовуючи метод head
Визначте розмір таблиці за допомогою методу shape
Визначте типи всіх стовпців за допомогою dataframe.dtypes
Порахуйте, яка частка пропусків міститься в кожній колонці (використовуйте методи isnull та sum)
Видаліть усі стовпці з пропусками, крім стовпця "Мова програмування"
Знову порахуйте, яка частка пропусків міститься в кожній колонці і переконайтеся, що залишився тільки стовпець "Мова.програмування"
Видаліть усі рядки у вихідній таблиці за допомогою методу dropna
Визначте новий розмір таблиці за допомогою методу shape
Створіть нову таблицю python_data, в якій будуть тільки рядки зі спеціалістами, які вказали мову програмування Python
Визначте розмір таблиці python_data за допомогою методу shape
Використовуючи метод groupby, виконайте групування за стовпчиком "Посада"
Створіть новий DataFrame, де для згрупованих даних за стовпчиком "Посада", виконайте агрегацію даних за допомогою методу agg і знайдіть мінімальне та максимальне значення у стовпчику "Зарплата.в.місяць"
Створіть функцію fill_avg_salary, яка повертатиме середнє значення заробітної плати на місяць. Використовуйте її для методу apply та створіть новий стовпчик "avg"
Створіть описову статистику за допомогою методу describe для нового стовпчика.
Збережіть отриману таблицю в CSV файл
Робота здається у вигляді Jupyter файлу Hw2.2.ipynb

### Частина третя: Аналіз датасет c Kaggle.com
У цій частині домашньої роботи ми ще більше заглибимося в бібліотеку pandas та розглянемо просунутіші функції.

Для цієї вправи ми використовуємо дані за Топ-50 рейтингом книг, що найбільше продаються на Amazon за 11 років (з 2009 по 2019). Датасет знаходиться у відкритому доступі на Kaggle.com. Завантажте файл csv за посиланням і перемістіть його в ту саму директорію, де знаходиться ваш робочий ноутбук (для зручності). Після цього переходьте до завдання

Для виконання цієї частини домашнього завдання потрібно буде не тільки написати код, а й відповісти на супутні запитання. Там, де ви побачите виділений жирним шрифтом напис відповідь: потрібно буде вставити питання у файл і відповідь на нього.

Наприклад:

Яка бібліотека використовується для роботи з датафреймами у python? Відповідь: pandas

#### Необхідно виконати:

Прочитайте csv файл (використовуйте функцію read_csv)
Виведіть перші п'ять рядків (використовується функція head)
Виведіть розміри датасету (використовуйте атрибут shape)
Відповідь: Про скільки книг зберігає дані датасет?
Для кожної з книг доступні 7 змінних (колонок). Давайте розглянемо їх детальніше:

Name - назва книги

Author - автор

User Rating - рейтинг (за 5-бальною шкалою)

Reviews - кількість відгуків

Price - ціна (у доларах станом на 2020 рік)

Year - рік, коли книга потрапила до рейтингу Топ-50

Genre - жанр

Для спрощення подальшої роботи давайте трохи підправимо назви змінних. Як бачите, тут усі назви починаються з великої літери, а одна - навіть містить пробіл. Це дуже небажано і може бути досить незручним. Давайте змінимо регістр на малий, а пробіл замінимо на нижнє підкреслення (snake_style). А заразом і вивчимо корисний атрибут датафрейму: columns (можна просто присвоїти список нових імен цьому атрибуту)

df.columns = ['name', 'author', 'user_rating', 'reviews', 'price', 'year', 'genre']

##### Первинне дослідження даних
Перевірте, чи у всіх рядків вистачає даних: виведіть кількість пропусків (na) у кожному зі стовпців (використовуйте функції isna та sum)
Відповідь: Чи є в якихось змінних пропуски? (Так / ні)
Перевірте, які є унікальні значення в колонці genre (використовуйте функцію unique)
Відповідь: Які є унікальні жанри?
Тепер подивіться на розподіл цін: побудуйте діаграму (використовуйте kind='hist')
Визначте, яка ціна у нас максимальна, мінімальна, середня, медіанна (використовуйте функції max, min, mean, median)
Відповідь: Максимальна ціна?
Відповідь: Мінімальна ціна?
Відповідь: Середня ціна?
Відповідь: Медіанна ціна?
Пошук та сортування даних
Відповідь: Який рейтинг у датасеті найвищий? Відповідь:
Відповідь: Скільки книг мають такий рейтинг? Відповідь:
Відповідь: Яка книга має найбільше відгуків? Відповідь:
Відповідь: З тих книг, що потрапили до Топ-50 у 2015 році, яка книга найдорожча (можна використати проміжний датафрейм)? Відповідь:
Відповідь: Скільки книг жанру Fiction потрапили до Топ-50 у 2010 році (використовуйте &)? Відповідь:
Відповідь: Скільки книг з рейтингом 4.9 потрапило до рейтингу у 2010 та 2011 роках (використовуйте | або функцію isin)? Відповідь:
І насамкінець, давайте відсортуємо за зростанням ціни всі книги, які потрапили до рейтингу в 2015 році і коштують дешевше за 8 доларів (використовуйте функцію sort_values).
Відповідь: Яка книга остання у відсортованому списку? Відповідь:

##### Агрегування даних та з'єднання таблиць

Остання секція цього домашнього завдання включає просунутіші функції. Але не хвилюйтеся, pandas робить усі операції простими та зрозумілими.

Для початку давайте подивимося на максимальну та мінімальну ціни для кожного з жанрів (використовуйте функції groupby та agg, для підрахунку мінімальних та максимальних значень використовуйте max та min). Не беріть усі стовпці, виберіть тільки потрібні вам

Відповідь: Максимальна ціна для жанру Fiction: Відповідь

Відповідь: Мінімальна ціна для жанру Fiction: Відповідь

Відповідь: Максимальна ціна для жанру Non Fiction: Відповідь

Відповідь: Мінімальна ціна для жанру Non Fiction: Відповідь

Тепер створіть новий датафрейм, який вміщатиме кількість книг для кожного з авторів (використовуйте функції groupby та agg, для підрахунку кількості використовуйте count). Не беріть усі стовпці, виберете тільки потрібні

Відповідь: Якої розмірності вийшла таблиця? Відповідь:

Відповідь: Який автор має найбільше книг? Відповідь:

Відповідь: Скільки книг цього автора? Відповідь:

Тепер створіть другий датафрейм, який буде вміщати середній рейтинг для кожного автора (використовуйте функції groupby та agg, для підрахунку середнього значення використовуйте mean). Не беріть усі стовпці, виберете тільки потрібні

Відповідь: У якого автора середній рейтинг мінімальний? Відповідь:

Відповідь: Який у цього автора середній рейтинг? Відповідь:

З'єднайте останні два датафрейми так, щоб для кожного автора було видно кількість книг та середній рейтинг (Використовуйте функцію concat з параметром axis=1). Збережіть результат у змінну

Відсортуйте датафрейм за зростаючою кількістю книг та зростаючим рейтингом (використовуйте функцію sort_values)

Відповідь: Який автор перший у списку?

Робота здається у вигляді Jupyter файлу Hw2.3.ipynb

##### Візуалізація
Для кожного з попередніх завдань:

Hw2.1.ipynb
Hw2.2.ipynb
Hw2.3.ipynb
додайте від 3 до 5 графіків функцій різного типу на ваш вибір. Задайте графікам оформлення, щоб кожен графік у своїй домашній роботі чимось відрізнявся і не був схожим на інші. Можна використовувати як matplotlib, так і seaborn.

Не забудьте в Jupyter файл додати директиву %matplotlib inline, щоб графіки будувалися всередині документа.

# Домашнє завдання - 3
Дане домашнє завдання буде повністю пов'язане з лінійною регресією та її реалізацією. Отож розіб'ємо наше домашнє завдання на декілька частин:

* напишіть функцію гіпотези лінійної регресії у векторному вигляді;
* створіть функцію для обчислення функції втрат у векторному вигляді;
* реалізуйте один крок градієнтного спуску;
* знайдіть найкращі параметри w для датасету Housing прогнозуючу ціну на будинок залежно від площі, кількості ванних кімнат та кількості спалень;
* знайдіть ці ж параметри за допомогою аналітичного рішення;
* порівняйте отримані результати.


# Домашнє завдання - 4

На цей раз вам потрібно виконати завдання з цього ноутбука. Для вирішення запропонованих завдань вам також потрібно завантажити датасет з даними про оренду велосипедів bikes_rent.

# Домашнє завдання - 5

В домашньому завданні до даного модулю ви потренуєтесь робити тестове завдання для влаштування на роботу. За даними акселерометра з мобільного телефону потрібно класифікувати, якою діяльністю займається людина: йде, стоїть, біжить чи йде по сходах. Знайти датасет ви можете за посиланням папка homework_5.

Використайте алгоритми SVM та випадковий ліс з бібліотеки scikit-learn. Як характеристики можете брати показники з акселерометра, проте щоб покращити результати роботи алгоритмів, спочатку можна підготувати наш датасет і розрахувати часові ознаки (time domain features). Більше ці характеристики описані в даній статті.

Порівняйте результати роботи обох алгоритмів на різних фічах та різні моделі між собою.

# Домашнє завдання - 6

Завдання, що пропонуються, необхідно оформити у вигляді одного jupyter ноутбука.

### Завдання 1
У цьому завданні вам потрібно завантажити ось цей датасет. Тут ви знайдете 2 файли - з двовимірним датасетом та датасетом mnist. Для кожного з них застосуйте алгоритм K-means для кластеризації. Щоб знайти оптимальну кількість кластерів, скористайтесь ліктевим методом.

### Завдання 2
Візуалізуйте результат роботи кластеризації. Для випадку з mnist датасетом, вам потрібно ще скористатись алгоримтом PCA щоб зменшити розмірність вашим даних до 2-вимірного варіанту.