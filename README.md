# EasyORM
The easy ORM Class for PHP
---
```
It`s a very easy orm in PHP project
It`s can you is better in you work for db 
It`s has the command 
It`s json file config
```

## config EasyORM
```
open /bin/easyorm.php
$config = [
    'dbhost' => DBHOST,
    'dbname' => DBNAME,
    'dbuser' => DBUSER,
    'dbpassword' => DBPASS,
];
$path = dirname(dirname(__FILE__)).'/db';
config you project config
```
---

## EasyORM cli
```
php bin/easyorm
you can see the command in you dosc or unix/linux shell
EasyORM Command Line Interface v1.0
Welcome to use EasyORM
orm
    orm:create:name        Create the crate table json file of name in your db path!
    orm:alter:name         Create the alter table json file of name in your db path!
    orm:run:name           run the orm file into the database!
```
---

## orm:create
```
php bin/easyorm orm:create:user201811
EasyORM has create file user201811.json in you db path
```
---

## orm:alter
```
php bin/easyorm orm:alter:admin201811
EasyORM has create file admin201811.json in you db path
It`s content 
{
    "table":"",
    "opration":"alter",
    "feilds":[
        {
            "name":"",
            "type":"",
            "length":"",
            "default":"",
            "comment":"",
            "after":""
        }
    ]
}
you can config you want do it
```
---

## orm:run
```
php bin/easyorm orm:run:user201811
EasyORM has update your database
```
---

## FAQ
```
Q:How to use it?
A:
```
