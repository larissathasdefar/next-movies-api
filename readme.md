# Next Movies API

A Laravel api that uses the TMDB for data and a [React.js frontend](https://github.com/larissathasdefar/next-movies) and the server is host [here](https://aqueous-woodland-85544.herokuapp.com/api/upcoming/page/1).

+--------+----------+---------------------------------+------+---------+------------+
| Domain | Method   | URI                             | Name | Action  | Middleware |
+--------+----------+---------------------------------+------+---------+------------+
|        | GET|HEAD | /                               |      | Closure | web        |
|        | GET|HEAD | api/genres                      |      | Closure | api        |
|        | GET|HEAD | api/movie/{id}                  |      | Closure | api        |
|        | GET|HEAD | api/search/{query}/page/{page?} |      | Closure | api        |
|        | GET|HEAD | api/upcoming/page/{page?}       |      | Closure | api        |
+--------+----------+---------------------------------+------+---------+------------+


## Run

```php artisan serve```
