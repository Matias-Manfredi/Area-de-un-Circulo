     //Area de un Circulo

     //Con import llamamos al paquete "util", que incluye la clase "Scanner", la cual usaremos para operar mediante interfaz usuario y programa
     import java.util.Scanner;

      class AreaDeUnCirculo 
     {  
      public static void main (String [] args) 
       {
    
      /* La clase scanner es la encargada de escanear los datos de entrada que el usuario dio a través de la consola.
       Debemos crear un objeto que sea la referencia para almacenar la variable “c”. 
       (Para obtener acceso a la consola debemos crear un objeto “new scanner”). 
      */
   
        Scanner c= new Scanner(System.in);
   
       //Ahora con System.out.println(“Ingresar el radio: ”); solicitamos al usuario itroduzca el valor del radio con teclado.  
      
       System.out.println("Ingresar el radio: ");
     
        //Utilizamos “nextdouble”, ya que es el formato que necesitamos para pi es el de un número con decimales.
     
       double r= c.mextDouble();
      
        //Para obtener el área de un círculo, debemos definir la fórmula que, como sabemos, consiste en A = r2 π:
        //El símbolo griego de “pi” se representaa con el valor de 22/7 (22/7=3,142857142857143)
      
        double area=(22 *r *r)/7;
      
       //devolvemos al usuario el resultado:
     
       System.out.println("El area del circulo es: " + area);
      
       }

    }
