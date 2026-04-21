1. Реализация
```python
def Value_in_arr(arr, search_value):
    for x in arr:
        if x == search_value:
            return True
    return False
```
2. Функция измерения времени
```python
import time

def measure_time(func, data):
    start = time.perf_counter()
    func(data)
    end = time.perf_counter()
    return end - start
```
3. Функция генерации данных
```python
import random

def generate_array(n):
    arr = []
    for i in range(n):
        arr.append(random.randint(0, 10000))
    return arr
```
4. Эксперимент
