# Table: employee

## Create Table Script

~~~sql
CREATE TABLE `springa2023team6`.`employee` (
        `emp_no` INT NOT NULL AUTO_INCREMENT,
        `username` VARCHAR(16) NOT NULL,
        `first_name` VARCHAR(14) NOT NULL,
        `last_name` VARCHAR(16) NOT NULL,
        `email` VARCHAR(255) NULL,
        `password` VARCHAR(32) NOT NULL,
        `create_time` TIMESTAMP NULL DEFAULT CURRENT_TIMESTAMP,
        PRIMARY KEY (`emp_no`));
~~~

## `Table`

| `Name`   | `Comment`               | `Schema`           | `Engine` |
| :-------- | :--------------------- | :----------------- | :-------- |
| employee | The department table.   | springa2023team6   | InnoDB   |

**When using the 'InnoDB' Relational Database Modeling Techniques(aka one pk per table), will be enforced**

## `Primary Key`

| `Columns` |
| :-------- |
| emp_no    |

## `Indexes`

## `Foreign Keys`

| `Columns` | `Ref Table` | `Ref Columns` | `Options` |
| --------- | ----------- | ------------- | --------- |
|           |             |               |           |

## `Columns`

| `Label`         | `Name`         | `Type`                                 | `Nullable` | `Default`           | `Comment`                    |
| :-------------- | :------------- | :------------------------------------- | :--------- | :------------------ | :--------------------------- |
| emp_no          | emp_no         | PK int auto_increment                  | `No`       |                     | Primary Key                  |
| username        | username       | varchar(16)                            | `No`       |                     | Login username               |
| first_name      | first_name     | varchar(14)                            | `No`       |                     | emp first name               |
| last_name       | last_name      | varchar(16)                            | `No`       |                     | emp last name                |
| email           | email          | varchar(255)                           | `Yes`      | ''                  | emp email                    |
| password        | password       | varchar(32)                            | `No`       |                     | Login password               |
| create_time     | create_time    | TIMESTAMP                              | `Yes`      | current_timestamp() | Time when record created     |
