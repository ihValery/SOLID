# S.O.L.I.D. На шаг ближе к чистой архитектуре

- S: Single Responsibility Principle (Принцип единственной ответственности).
- O: Open-Closed Principle (Принцип открытости-закрытости).
- L: Liskov Substitution Principle (Принцип подстановки Барбары Лисков).
- I: Interface Segregation Principle (Принцип разделения интерфейса).
- D: Dependency Inversion Principle (Принцип инверсии зависимостей).

- 1. Изучаем теоретическую составляющую каждого принципа SOLID
- 2. Разбираемся с применением каждого принципа на практических примерах
- 3. Смотрим как применяются SOLID принципы в рамках реального приложения
- 4. Учимся думать перед тем, как бросаться писать код

1. YAGNI (You Aren’t Gonna Need It / Вам это не понадобится)
Принцип прост и очевиден, но ему далеко не все следуют. Если пишешь код, то будь уверены, что он тебе понадобится. Не пиши код, если думаешь, что он пригодится позже.
2. DRY (Don’t Repeat Yourself / Не повторяйтесь)
Дублирование кода – пустая трата времени и ресурсов. Тебе придется поддерживать одну и ту же логику и тестировать код сразу в двух местах, причем если ты меняешь код в одном месте, его нужно будет изменить и в другом
3. KISS (Keep It Simple, Stupid / Будь проще)
Не придумывай к задаче более сложного решения, чем ей требуется.
Самое разумное решение оказывается и самым простым. Написание производительного, эффективного и простого кода – это прекрасно.
