import java.util.Scanner;
class Main {
  public static void main(String[] args) {
  Scanner dato = new Scanner(System.in) ;
 
 String nombre;
  Scanner sc = new Scanner(System.in);
    System.out.println("ingrese el nombre: ");
    nombre = sc.nextLine();
    
    int parcial = 0;
  System.out.println("1casilla nota tarea: ");
    int primera = dato.nextInt();
    System.out.println("2casilla nota tarea: ");
     int segunda = dato.nextInt();
    System.out.println("3casilla nota tarea: ");
     int tercera = dato.nextInt();
    System.out.println("4casilla nota examen: ");
     int cuarta = dato.nextInt();
    
    System.out.println("primer parcial "+(primera+segunda+tercera+cuarta)/4);

    

   
  
  }
  
}