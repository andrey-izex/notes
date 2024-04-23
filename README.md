# notes

## Вырезка дампа таблицы MySQL
```
sed -n -e '/DROP TABLE.*`table_name`/,/UNLOCK TABLES/p' dump.sql > tabledump.sql

```



