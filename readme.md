## Теоретичні питання

1. Опишіть своїми словами, що таке екранування, і навіщо воно потрібне в мовах програмування
   Екранування символів означає, що ми робий з ними щось, щоб бути впевненими, що вони будуть розпізнаватись як текст, а не частина коду
2. Які засоби оголошення функцій ви знаєте?
декларація, експерсія і стрілкові
3. Що таке hoisting, як він працює для змінних та функцій?
   Підйом, коли при оголошенні функції інтерпретатор знає заздалегідь про всі локальні змінні цієї функції, тому він піднімає оголошення всіх змінних на початок функції без ініціалізації.

## Завдання

Доповнити функцію createNewUser() методами підрахунку віку користувача та його паролем. Завдання має бути виконане на чистому Javascript без використання бібліотек типу jQuery або React.

#### Технічні вимоги:

- Візьміть виконане домашнє завдання номер 4 (створена вами функція createNewUser()) і доповніть її наступним функціоналом:
  1. При виклику функція повинна запитати дату народження (текст у форматі `dd.mm.yyyy`) і зберегти її в полі `birthday`.
  2. Створити метод `getAge()` який повертатиме скільки користувачеві років.
  3. Створити метод `getPassword()`, який повертатиме першу літеру імені користувача у верхньому регістрі, з'єднану з прізвищем (у нижньому регістрі) та роком народження. (наприклад, `Ivan Kravchenko 13.03.1992 → Ikravchenko1992`.
- Вивести в консоль результат роботи функції `createNewUser()`, а також функцій `getAge()` та `getPassword()` створеного об'єкта.

#### Література:

- [Дата і час](https://learn.javascript.ru/datetime)
