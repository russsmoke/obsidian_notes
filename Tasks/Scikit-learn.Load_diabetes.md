
```dataview 	
TABLE without id	
file.outlinks AS "OUTGOING", 	
file.inlinks AS "BACKLINKS"	
WHERE file.name = this.file.name 
```

#reference

# Links
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html - полное руководство по датасету.
[[Python]]
# Description
![[Pasted image 20260224152647.png]]
![[Pasted image 20260224151359.png]]

Данные представляют собой словарь с ключами `data, target, feature_names, frame, DESCR:str, data_filename:str, target_filename:str`
- data: матрица данных (442, 10). *Dataframe (as_frame=True)*
- target: одномерный массив (442,). *Series (as_frame=True)*
- feature_names: list с названиями атрибутов
- frame: *(as_frame=True)* DataFrame c data и target

***Features***
- Age - возраст в годах
- 
