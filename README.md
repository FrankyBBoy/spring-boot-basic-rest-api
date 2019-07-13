# spring-boot-basic-rest-api

### To make it work locally:
1. Install my SQL
2. Run these commands:
```
CREATE DATABASE restapi;

USE restapi;

CREATE TABLE blog (
  id INT(6) UNSIGNED AUTO_INCREMENT PRIMARY KEY,
  title VARCHAR(500) NOT NULL,
  content VARCHAR(5000) NOT NULL
);

SET @@global.time_zone = '+05:00';
```
