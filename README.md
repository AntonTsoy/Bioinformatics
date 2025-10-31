# Визуализация структуры белка

## О работе

Название ПО для визуализации: **UCSF ChimeraX**

Ссылка на структуру белка: https://www.rcsb.org/structure/8XJ4

## Визуализации

Открываем во вкладке `Open` наш PDB файл. Затем отключаем режим ленточек в коммандной строке:
```cli
hide cartoons
```

### Wireframe


Команды для визуализации атомов и связей, как тонких стержней, а также показа элементов:
```cli
style #1 stick
show #1
```

### Backbone


Команды:
```cli
hide atoms
show cartoons
cartoon style #1 modeHelix tube
```

### Spacefill
