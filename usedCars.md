# Lista delle auto usate

| name           | type        | attributes                          | key     |
| -------------- | ----------- | ----------------------------------- | ------- |
| id             | BIGINT(20)  | NOT NULL - AUTOINCREMENT - UNSIGNED | PRIMARY |
| plate_number   | VARCHAR(7)  |                                     |         |
| brand          | VARCHAR(40) | NOT NULL                            |         |
| model          | VARCHAR(40) | NOT NULL                            |         |
| kilometers     | MEDIUMINT   | NOT NULL - DEFAULT(0) - UNSIGNED    |         |
| fuel           | CHAR(1)     | NOT NULL                            |         |
| conditions     | CHAR(1)     | NOT NULL                            |         |
| color_EX       | VARCHAR(7)  | NOT NULL                            |         |
| owners_numbers | TINYINT     | NOT NULL - DEFAULT(0) - UNSIGNED    |         |
| year           | YEAR        | NOT NULL - UNSIGNED                 |         |
