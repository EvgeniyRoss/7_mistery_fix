# Решатель квадратных уравнений

Модуль quadratic_equation позволяет найти корни квадратного уравнения вида a * x^2 + b * x + c = 0

# Как использовать

В модуль встроена функция get_roots(a, b, c). Функция принимает на вход коэффициенты квадратного уравнения и возвращает его корни.
Пример решения уравнения: 2 * x^2 + 9 * x + 1 = 0

    from quadratic_equation import get_roots
    
    
    print(get_roots(2, 9, 1))

Ответ: -4.4, -0.1

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
