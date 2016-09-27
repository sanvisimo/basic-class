## Synopsis

A simple class with MySQL connection and methods to send queries or get value/s from DB

## Code Example
```php
    include('php/classe.php');
    $classe = new Classe;
    $query="SELECT * FROM contenuto";
    echo $classe->getDbValues($query);
```

## Motivation

A little PHP mysqli sample
