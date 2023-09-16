```python
for i in range(10):
	pass
	
array = [1, 2, 3, 4, 5]
for j in array:
	print(j) 
```
Первый  цикл перебирает  цифры из `range()`
Второй перебирает элементы из `array` по порядку

> [!note] `range(start, end, step):`
> Перебирает от  `start`  включительно до `end` , но уже **не включая его**  
> `step` изменение за один шаг перебора

```python
for name in range(3, 18, 3):
	print(name, ' ') # выводит 3 6 9 12 15
```

```python
for name in range(12, 2, -2):
	print(name, ' ') # выводит 12 10 8 6 4
```

#циклы
![[Pasted image 20230916225239.png]]