---
title: "Mysql CheatSheet"
categories: "mysql"
---

#### Mysql Connecion

| 명령어                  | 설명                      |
| ----------------------- | ------------------------- |
| `mysql -u${account} -p` | mysql connection with cmd |

#### Workbench

```mysql
\func now()
```

#### Select

```
SELECT _ FROM table;
SELECT _ FROM table1, table2;
SELECT field1, field2 FROM table1, table2;
SELECT ... FROM ... WHERE condition
SELECT ... FROM ... WHERE condition GROUP BY field;
SELECT ... FROM ... WHERE condition GROUP BY field HAVING condition2;
SELECT ... FROM ... WHERE condition ORDER BY field1, field2;
SELECT ... FROM ... WHERE condition ORDER BY field1, field2 DESC;
SELECT ... FROM ... WHERE condition LIMIT 10;
SELECT DISTINCT field1 FROM ...
SELECT DISTINCT field1, field2 FROM ...
```
