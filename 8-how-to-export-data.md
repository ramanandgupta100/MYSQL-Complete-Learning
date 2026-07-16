# How to Export Data?

## Export Database

```
mysqldump -u root -p database > database.sql

Example:
mysqldump -u root -p students > students.sql
```

## Export Table

```
mysqldump -u root -p database table > table.sql

Example:
mysqldump -u root -p students attendance > attendance.sql
```

