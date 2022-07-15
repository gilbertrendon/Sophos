# Sophos
Toma una evidencia de que has finalizado la prueba y nos la compartes vía correo, debe
ser algo así, en este caso si puedes tomar una impresión de pantalla

# Página para querys sql
https://sqliteonline.com/https://sqliteonline.com/

# ... java 
https://www.jdoodle.com/online-java-compiler/


SELECT * FROM products

CREATE TABLE Usuarios  
   (ID int PRIMARY KEY NOT NULL,  
   NAME varchar(25) NOT NULL,  
   EMAIL money NULL)  

INSERT INTO products (ProductID, ProductName, Price) 
VALUES (1,"arroz", 10);

DELETE FROM products where ProductID = 1

INSERT INTO products (ProductID, ProductName, Price) 
VALUES (1,"Producto1", 18000);

INSERT INTO products (ProductID, ProductName, Price) 
VALUES (2,"Producto2", 19000);


INSERT INTO products (ProductID, ProductName, Price) 
VALUES (3,"Producto3", 10500);


INSERT INTO products (ProductID, ProductName, Price) 
VALUES (4,"Producto4", 22300);


INSERT INTO products (ProductID, ProductName, Price) 
VALUES (5,"Producto5", 21150);


select * from products where price > 12000 AND price  < 20000
select * from products where price in (12000,20000)
select * from products where price between 12000 and 20000
select * from products having price >= 12000 and price <= 20000


--------------
INSERT INTO usuarios (ID, NAME, EMAIL) 
VALUES (1,"John", "asd@asd.com");

INSERT INTO usuarios (ID, NAME, EMAIL) 
VALUES (2,"Sam", "asd@asd.com");

INSERT INTO usuarios (ID, NAME, EMAIL) 
VALUES (3,"Tom", "asd@asd.com");

INSERT INTO usuarios (ID, NAME, EMAIL) 
VALUES (4,"Bob", "asd@asd.com");

INSERT INTO usuarios (ID, NAME, EMAIL) 
VALUES (5,"Tom", "asd@asd.com");

select name,email,count(*) as countof
from usuarios
group by name, email
having count(*)>1

String greeting = "Hello world";