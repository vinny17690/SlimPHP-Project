# SlimApp RESTful API

This is a RESTful api built using SlimPHP framework and uses MySQL Database for storage.

### Version Number
1.0.5

### Prerequisites
Need to setup SlimPHP Framework, XAMPP/WAMP (XAMPP/WAMP also gives access to MySQL database as well on port 3306)

### Installation

Create database or import from _sql/slimapp.sql

Edit db/config params

Install SlimPHP and dependencies

```sh
$ composer
```
### API Endpoints (Useful to test the application right out of the box)
```sh
$ GET /api/customers
$ GET /api/customer/{id}
$ POST /api/customer/add
$ PUT /api/customer/update/{id}
$ DELETE /api/customer/delete/{id}
```
