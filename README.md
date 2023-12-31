# Домашнє завдання #10

У минулій домашній роботі ви виконували скрапінг сайту [http://quotes.toscrape.com](http://quotes.toscrape.com).

### Вам необхідно самостійно реалізувати аналог такого сайту на Django.

1. Додайте можливість реєстрації та входу на сайт.
2. Додайте можливість додавання нового автора тільки для зареєстрованого користувача.
3. Додайте можливість додавання нової цитати з вказанням автора тільки для зареєстрованого користувача.
4. Виконайте міграцію бази даних з MongoDB у Postgres для вашого сайту (можливо, кастомним скриптом).
5. Дозвольте перегляд сторінки кожного автора без автентифікації користувача.
6. Забезпечте доступ до всіх цитат без автентифікації користувача.

### Додаткова частина

1. Реалізуйте пошук цитат за тегами. При натисканні на тег виводьте список цитат з цим тегом.
2. Додайте блок "Top Ten tags" та виведіть найпопулярніші теги.
3. Реалізуйте пагінацію з кнопками "next" та "previous".
4. Замість перенесення даних з бази даних MongoDB, реалізуйте можливість скрапінгу даних з вашого сайту прямо при натисканні певної кнопки на формі та наповнення бази даних сайту.
