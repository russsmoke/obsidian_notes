
```dataview 	
TABLE without id	
file.outlinks AS "OUTGOING", 	
file.inlinks AS "BACKLINKS"	
WHERE file.name = this.file.name 
```

#reference #программирование #python

# Links
Подробное описание возможностей f-строк: https://docs.python.org/3/tutorial/inputoutput.html#formatted-string-literals
[[Python]]
# Description
1) Команда форматирования f-строки `f"{123:0>9}"` выведет `000000123`
   ![[Pasted image 20260113154251.png]]
   Другие примеры:
   ```
   print(f"{7:0>5}")    # 00007
   print(f"{42:*<6}")   # 42**** (выравнивание влево)
   print(f"{15:^6}")    #  15   (выравнивание по центру)
   print(f"{3.14:.2f}") # 3.14 (форматирование float)
   ```
   2) `format()` 
      ```
      print("Привет, {}!".format(name))
      ```
      