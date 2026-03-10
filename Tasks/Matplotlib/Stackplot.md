
```dataview 	
TABLE without id	
file.outlinks AS "OUTGOING", 	
file.inlinks AS "BACKLINKS"	
WHERE file.name = this.file.name 
```

#reference

# Links
[[Matplotlib]]
[[Python]]
# Description
Функция, которая создает стековый или сложенный график, где несколько временных рядов (или любых данных) отображаются один над другим, формируя суммарную область.
Это позволяет легко визуализировать:
- общую сумму всех компонентов в единицу времени
- Вклад каждого компонента в эту сумму
- Изменение структуры (долей) компонентов
```
import numpy as np #
import matplotlib.pyplot as plt #

# задаем данные
rng = np.arange(50) #
rnd = np.random.randint(0, 10, size=(3, rng.size)) #
yrs = 1950 + rng #

fig, ax = plt.subplots(figsize=(5, 3)) # создаем полотно заданного размера
ax.stackplot(yrs, rng + rnd, labels=['Eastasia', 'Eurasia', 'Oceania']) # рисуем линии графиков, указав данные по оси х,оси у и названия графиков (метки)

```
