# iXperience - Full Stack

Welcome to iXperience Full Stack 2019!

[[toc]]

## MySQL  

### Create Database

Run the following SQL query to create a database called fs_bnb

```sql

CREATE DATABASE fs_bnb 

```

### Create Table

Run the following query to create a table called listing. The table has a primary key: id and fields userId, title, description, location and pricePerNight.

```sql

CREATE TABLE `fs_bnb`.`listing` (
  `id` INT(6) UNSIGNED NOT NULL AUTO_INCREMENT PRIMARY KEY,
  `userId` INT(6) UNSIGNED NOT NULL,
  `title` VARCHAR(45) NOT NULL,
  `description` VARCHAR(45) NULL,
  `location` VARCHAR(45) NULL,
  `pricePerNight` DECIMAL(10) NOT NULL
)

```

### Insert Data into Table

Run the following query to insert data in the listing table. The insert query contains data for the fields userId, title, description, location and pricePerNight.

```sql

INSERT INTO fs_bnb.listing (userId, title, description, location, pricePerNight)
VALUES (2, "Hout Bay Town House", "Town House", "Hout Bay", "120")

```