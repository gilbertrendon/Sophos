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
# Pruebitas

// def arrayDesc():
//   desc = True
//   asc = True
//   i=0
//   j=1
//   while j<len(arr)
//     if desc or asc:
//       if arr[i] < arr[j]:
//         desc = False
//       if arr[i] > arr[j]:
//         acs = False
//     else:
//       break
//     i += 1
//     j += 1
//   if asc or desc:
//     if asc and desc:
//       return 'TODOS_IGUALES'
//     return 'ASC' if asc else 'DESC'
//   else:
//      return 'DESORDENADO'
     
// res = arrayDesc([0,1,2,10,2,3,3])
  


public class TestJose{
    public void arrayDesc(){
        Boolean desc = true;
        Boolean asc = true;
        int i = 0;
        int j = 1;
        // while j < len()
        
    }
    public static void main(String args[]) {
        TestJose TJ = new TestJose();
        TJ.arrayDesc();
        int[] arr = new int[4];
        int c=0;
        while(c<4){
            // System.out.println(arr.length());
            c+=1;
        }
    }
    
}

// public class TestJose {
//     public static void main(String args[]) {
//       int x=10;
//       int y=25;
//       int z=x+y;

//       System.out.println("Sum of x+y = " + z);
//     }
// }


---------------------------------------------------------------------------------------
select department_name, count(A.id) from APPX_employee as A
INNER JOIN APPX_department as B
ON A.department_id = B.id


for(int i = 0; i < 100; i++) 


public static void main (String args[]) {
  // Your code here
  //int matriz[][] = new int[1][8];
  int len = n;
  Boolean symetric = true;
  //System.out.println(n);
	for(int j=0;j<len;j++){
		if((myArray[j] == myArray[len-1])&&(j<=len-1)){
			symetric = true;
		}else{
			symetric = false;
		}
	}
  if(symetric == true){
  	System.out.println("Symetric");
  }else{
  	System.out.println("No symetric");
  }
}


-----------------------------
public static void main (String args[]) {
   // Your code here
  int len = myArray.length;
	for(int i=0;i<len;i++){
		for(int j=i+1;j<len;j++){
			if(myArray[i] + myArray[j] == 10){
				System.out.println(myArray[i]+" "+myArray[j]);
			  	break;
			}
		}
	}
}
