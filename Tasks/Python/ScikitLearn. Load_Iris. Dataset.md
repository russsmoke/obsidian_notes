
```dataview 	
TABLE without id	
file.outlinks AS "OUTGOING", 	
file.inlinks AS "BACKLINKS"	
WHERE file.name = this.file.name 
```

#reference

# Links
https://sky.pro/wiki/analytics/analiz-i-rabota-s-iris-dataset-v-python-polnoe-rukovodstvo/ - полное руководство использования данного датасета
[[Python]]
# Description
В библиотеке ScikitLearn есть тестовый датасет по цветкам ириса. Содержит 150 образцов растений трех классов: Iris Setosa, Iris verginica, Iris versicolor. По 50 образцов каждого класса. Сами данные представляют собой описание по 4 характеристикам: длина чашелистика, ширина чашелистика, длина лепестка, ширина лепестка.