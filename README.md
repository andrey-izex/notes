# notes

## Вырезка дампа таблицы MySQL
```
sed -n -e '/DROP TABLE.*`table_name`/,/UNLOCK TABLES/p' dump.sql > tabledump.sql

```



@startuml
Bob -> Alice : hello
Bob <- Alice : hello3
Bob <- Max : hello4
@enduml

```plantuml
Bob -> Alice : hello
Alice -> Bob : hi
```
