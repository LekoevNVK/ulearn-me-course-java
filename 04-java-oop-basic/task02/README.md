# Задание 02 - Временной интервал

Создайте класс TimeSpan, который будет хранить временной интервал в часах, минутах и секундах (каждый в отдельном поле).
Все поля должны быть объявлены как `private`, т.е. скрыты от прямого доступа снаружи. Для каждого поля добавить пару `public` методов,
один из которых будет получать (get) значение поля, другой - выставлять (set).
Для класса нужно описать конструктор, который принимает на вход три параметра и инициализирует свое состояние по ним.

Добавьте метод `void add(TimeSpan time)`, который должен прибавлять к текущему интервалу значение переданного интервала

Добавьте метод `void subtract(TimeSpan time)`, который должен вычитать из текущего интервала значение переданного интервала

Добавьте метод `public String toString()`, который должен возвращать строковое представление интервала в любом удобном виде