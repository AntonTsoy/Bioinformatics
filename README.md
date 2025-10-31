# Визуализация структуры белка

## О работе

Название ПО для визуализации: **UCSF ChimeraX**

Ссылка на структуру белка: https://www.rcsb.org/structure/8XJ4

## Визуализации

Открываем во вкладке `Open` наш PDB файл.

!

### Wireframe

Используем коммандную строку. Отключаем режим ленточек, включаем режим атомов, визуализируем их как тонкие стержни:
```cli
hide cartoons
show atoms
style #1 stick
```

!

### Backbone

Команды:
```cli
hide atoms
show cartoons
cartoon style #1 modeHelix tube
```

!

### Spacefill

Команды:
```cli
hide cartoons
show atoms
style #1 sphere
```

!

### Ribbons

Команды:
```cli
hide atoms
show cartoons
cartoon style #1 modeHelix default
```

!

### Molecular surface

Команды:
```cli
hide cartoons
show atoms
surface #1
```

!
