## BEGIN
```
mysql -u root
```
## SHOW HOST AND PORT
- show host:
```
SELECT @@hostname;
```
- show port:
```
SHOW VARIABLES LIKE 'port';
```
- show host and port
```
SELECT @@hostname AS 'Host', @@port AS 'Port';
```
## SHOW DATABASES
```
show databases
```
## CLEAN CTRL + L

## CREATE DATABASE
``` CRATE DATABASE ```
## USE DATABASE
``` USE <mydatabase>```
## DROP DATABASE
```
DROP DATABASE <mydatabase>;
```
## CREATE TABLE
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(255) NOT NULL
);
## SHOW ALL TABLES
``` SHOW TABLES ```
## DROP TABLE 
``` DROP TABLE <mytable>```
## SHOW ALL PROCEDURE AND FUCNTION
```
SHOW PROCEDURE STATUS
```
```
 SHOW ALL PROCEDURE AND FUCNTION
```
## SHOW VALUE 
```
DESC <nametable>
```

