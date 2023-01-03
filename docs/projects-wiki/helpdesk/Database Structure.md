## networks

| column   | type        | comment |
| -------- | ----------- | ------- |
| id       | int         | PRIMARY AI      |
| network  | varchar(50) |         |
| client   | varchar(50) |         |
| location | varchar(50) |         |
| router   | varchar(50) |         |
| nat      | bool        |         |
| static   | bool        |         |

## router

| column   | type        | comment |
| -------- | ----------- | ------- |
| id       | int         | PRIMARY AI      |
| router   | varchar(50) |         |
| address  | varchar(50) |         |
| login    | varchar(50) |         |
| password | varchar(50) |         |
