# Sophos
Toma una evidencia de que has finalizado la prueba y nos la compartes vía correo, debe
ser algo así, en este caso si puedes tomar una impresión de pantalla

# Página para querys sql
https://sqliteonline.com/https://sqliteonline.com/

# ... java 
https://www.jdoodle.com/online-java-compiler/


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