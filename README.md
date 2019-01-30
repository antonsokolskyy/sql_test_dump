## SQL test dump
* Dumped from postgresql version 10.5
* Dumped by pg_dump version 10.5
## Schema
`Items` table:
* `id` serial primary key
* `name` varchar(255)

`Customers` table:
* `id` serial primary key
* `first_name` varchar(255)
* `last_name` varchar(255)

`CustomersItems` table:
* `price` decimal
* `item_id` int not null (referenced foreign key)
* `customer_id` int not null (referenced foreign key)