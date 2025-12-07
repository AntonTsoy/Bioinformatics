# Визуализация структуры белка

Выполнил: **Цой Антон 22214**

## О работе

Название ПО для визуализации: **UCSF ChimeraX** (https://www.cgl.ucsf.edu/chimerax/)

Ссылка на структуру белка: https://www.rcsb.org/structure/8XJ4

## Визуализации

Открываем во вкладке `Open` наш PDB файл.

![](sources/0.png)

### Wireframe

Используем коммандную строку. Отключаем режим ленточек, включаем режим атомов, визуализируем их как тонкие стержни:
```cli
hide cartoons
show atoms
style stick
```

![](sources/1.png)

### Backbone

Команды:
```cli
hide atoms
show cartoons
cartoon style modeHelix tube
```

![](sources/2.png)

### Spacefill

Команды:
```cli
hide cartoons
show atoms
style sphere
```

![](sources/3.png)

### Ribbons

Команды:
```cli
hide atoms
show cartoons
cartoon style modeHelix default
```

![](sources/4.png)

### Molecular surface

Команды:
```cli
hide cartoons
show atoms
surface
```

![](sources/5.png)

## Раскраска

### Цветовой моделью CPK

Команды:
```cli
hide surface
style stick
color byelement
```

![](sources/6.png)

### Различными цветами по доменам (частям) белка

Команды:
```cli
show cartoons
rainbow :1-150
```

![](sources/7.png)

## Изображение белка публикационного качества

![](sources/8.png)
![](sources/9.png)
