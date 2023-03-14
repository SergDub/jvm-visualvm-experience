# Домашнее задание для Netology.ru для курса Java Developer   

## Задача "Исследование JVM через VisualVM"

### Пояснения к результатам выполнения программы

        14:00:11.168: loading io.vertx
        загрузка классов в metaspace

        14:00:11.795: loaded 529 classes
        классы загружены (точка 1)

        14:00:14.811: loading io.netty
        загрузка классов в metaspace

        14:00:16.033: loaded 2117 classes
        классы загружены (точка 2)

        14:00:19.033: loading org.springframework
        загрузка классов в metaspace

        14:00:19.460: loaded 869 classes
        классы загружены (точка 3)
        происходит уменьшение heap за счет работы Garbage Collector

        14:00:22.460: now see heap
        14:00:22.461: creating 5000000 objects
        создание объектов

        14:00:22.883: created
        объем heap и зарезервированной памяти растет (точка 4)

        14:00:25.884: creating 5000000 objects
        создание объектов

        14:00:26.256: created
        объем heap и зарезервированной памяти растет (точка 5)

        14:00:29.340: creating 5000000 objects
        создание объектов

        14:00:29.844: created
        объем heap и зарезервированной памяти растет (точка 6)
        происходит уменьшение heap за счет работы Garbage Collector

<img src="file:///C:/Users/Nina/Downloads/heap.jpg" />

![](C:\Users\Nina\Downloads\heap.jpg)

![](C:\Users\Nina\Downloads\metaspace.jpg)
