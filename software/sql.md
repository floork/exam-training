# SQL

[Zurück zur Übersicht](../readme.md)

## Gliederung

- [SQL-Abfragen](#sql-abfragen)
- [Joins](#joins)
- [Quellen](#quellen)

---
---

## SQL-Abfragen

Häufig verwendete Statements:

- `SELECT` holt Daten aus Datenbank
- `UPDATE` updated Daten in der Datenbank
- `DELETE` löscht Daten aus Datenbank
- `INSERT INTO` bringt neue Daten in die Datenbank
- `CREATE DATABASE` erstellt neue Datenbank
- `ALTER DATABASE` modifiziert die Datenbank
- `CREATE TABLE` erstellt neue Tabelle
- `ALTER TABLE` modifiziert die Tabelle
- `DROP TABLE` löscht die Tabelle
- `CREATE INDEX` erstellt einen Index
- `DROP INDEX` löscht Index

Beispiele:

```sql
SELECT * FROM tablename
```

- zeigt alle Daten der Tablle an (`*` = alles)

```sql
SELECT column1, column2 FROM table_name
```

- zeigt `column1` und `column1` an

```sql
SELECT * FROM table_name WHERE condition
```

- zeigt alle Daten der Tabelle an, wo `condtion` erfüllt ist

```sql
SELECT * FROM Customers ORDER BY Country;
```

- zeigt alle Daten der Tabelle sortiert nach `Country`

```sql
INSERT INTO Customers (CustomerName, ContactName, Address, City, PostalCode, Country)
VALUES ('Cardinal', 'Tom B. Erichsen', 'Skagen 21', 'Stavanger', '4006', 'Norway');
```

- Setzt Werte in Tabelle ein

[Mehr](https://www.w3schools.com/sql/default.asp)

[Hoch](#gliederung)

---
---

## Joins

- wird verwendet, um Zeilen aus zwei oder mehr Tabellen zu kombinieren, basierend auf einer verwandten Spalte zwischen ihnen.

### Inner Join

![Abb. 1 (Inner Join)](./img/img_innerjoin.gif)

Abb. 1 [Quelle](https://www.w3schools.com/sql/sql_join_inner.asp)

```sql
SELECT column_name(s)
FROM table1
INNER JOIN table2
ON table1.column_name = table2.column_name;
```

### Left Join

![Abb. 2 (Left Join)](./img/img_leftjoin.gif)

Abb. 2 [Quelle](https://www.w3schools.com/sql/sql_join_left.asp)

```sql
SELECT column_name(s)
FROM table1
LEFT JOIN table2
ON table1.column_name = table2.column_name;
```

### Right Join

![Abb. 3 (Right Join)](./img/img_rightjoin.gif)

Abb. 3 [Quelle](https://www.w3schools.com/sql/sql_join_right.asp)

```sql
SELECT column_name(s)
FROM table1
RIGHT JOIN table2
ON table1.column_name = table2.column_name;
```

[Hoch](#gliederung)

---
---

## Quellen

### Inahlt

- <https://www.w3schools.com/sql/sql_syntax.asp>
- <https://www.w3schools.com/sql/sql_where.asp>
- <https://www.w3schools.com/sql/sql_insert.asp>
- <https://www.w3schools.com/sql/sql_join_inner.asp>
- <https://www.w3schools.com/sql/sql_join_left.asp>
- <https://www.w3schools.com/sql/sql_join_right.asp>

### Abbildungen

- Abb. 1: <https://www.w3schools.com/sql/sql_join_inner.asp>
- Abb. 2: <https://www.w3schools.com/sql/sql_join_left.asp>
- Abb. 3: <https://www.w3schools.com/sql/sql_join_right.asp>

[Hoch](#gliederung)

---
---
