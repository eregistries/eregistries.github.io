# Верифікація даних фізичних осіб
- **Функціонал [Електронного сервісу верифікації інформації про фізичних осіб](../readme.md)**

## Принцип роботи
- отримує довільний[^1] набір персональних даних фізичної особи
- [x] #1
- виконує:
    - пошук даних фізичної особи у [базі верифікованих даних фізичних осіб](../database/readme.md))
    - порівняння отриманого набору даних зі знайденими даними фізичної особи
- повертає:
    - статус однозначної ідентифікації фізичної особи на основі отриманого набору даних
    - ідентифікатори фізичної особи
        - УНЗР
        - РНОКПП
    - перелік атрибутів[^2], які відрізняються за результатами порівняння отриманого набору даних зі знайденими даними фізичної особи

[^1]: Потрібно деталізувати який
[^2]: Перелік атрибутів або список атрибутів