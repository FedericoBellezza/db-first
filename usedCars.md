# Lista delle auto usate

| name           | type        | attributes                          | key     |
| -------------- | ----------- | ----------------------------------- | ------- |
| id             | BIGINT(20)  | NOT NULL - AUTOINCREMENT - UNSIGNED | PRIMARY |
| plate_number   | VARCHAR(7)  |                                     |         |
| brand          | VARCHAR(40) | NOT_NULL                            |         |
| model          | VARCHAR(40) | NOT_NULL                            |         |
| kilometers     | MEDIUMINT   | NOT_NULL - DEFAULT(0) - UNSIGNED    |         |
| fuel           | CHAR(1)     | NOT_NULL                            |         |
| conditions     | CHAR(1)     | NOT_NULL                            |         |
| color_EX       | CHAR(6)     | NOT_NULL                            |         |
| owners_numbers | CHAR(3)     | NOT_NULL - DEFAULT(0) - UNSIGNED    |         |
| year           | CHAR(4)     | NOT_NULL - UNSIGNED                 |         |
