


			Universidad de colima 
			
			Facultad de Telematica

		Carlos Eduardo Damian Perez
		
		Interaccion humano computador actividad(clase)

Entrada de dos numeros enteros 
import java.util.Scanner;
import java.lang.Math;




public class tarea {
	public void entradaEnteros(){
		Scanner scan= new Scanner(System.in);
			System.out.println("Ingresa dos numeros");
		int a = scan.nextInt();
		int b = scan.nextInt();
			System.out.println(a);
			System.out.println(b);
			System.out.println("Fin Metodo Entrada Enteros");
	}	
	
	public void DobleeEntero(){
		int triple,doble;
		Scanner scan= new Scanner(System.in);
			System.out.println("Ingresa numero");
		int a = scan.nextInt();
		doble=a*2;
		triple=a*3;
			System.out.println(doble);
			System.out.println(triple);
		
			System.out.println("Fin Metodo Doble entero");
	}
	
	public void Circunferencia(){
		double radio,log,area,prueba;
		Scanner scan= new Scanner(System.in);
			System.out.println("Ingresa Radio");
		 radio = scan.nextInt();
		 log=2*Math.PI*radio;
		 area=Math.PI*Math.pow(radio, 2);
		 	System.out.println(log);
		 	System.out.println(area);
		
		System.out.println("Fin Metodo Circunferencia");
	}
	public static void main(String[]args){
		tarea t1= new tarea();
		t1.entradaEnteros();
		t1.DobleeEntero();
		t1.Circunferencia();
		
	}

}

--------------------------------------------------------------------------------------------------------------------------------------
Cadenas y velocidades
import java.util.Scanner;




public class tarea {
	public void Cadena(){
		Scanner scan= new Scanner(System.in);
			System.out.println("Ingresa Nombre");
		String a = scan.nextLine();
			System.out.println("Buenos Dias "+ a);
	}	
	
	public void GradosCentigrados(){
		double F,C;
		Scanner scan= new Scanner(System.in);
			System.out.println("Ingresa Temperatura");
		 C = scan.nextInt();
		 
		F=32+(9*C/5);			
			System.out.println("Temperatura en Fahrenheit " + F);
			System.out.println("Fin Metodo GradosCentigrados");
	}
	
	public void Velocidad(){
		double velocidad;
		Scanner scan= new Scanner(System.in);
			System.out.println("Ingresa Velocidad");
		 velocidad = scan.nextInt();		 
		 	System.out.println(velocidad+"KM/H "+ "=" +velocidad*1000/3600+"m/s" );
		 	
		
		System.out.println("Fin Metodo Circunferencia");
	}
	public static void main(String[]args){
		tarea t1= new tarea();
		t1.Cadena();
		t1.GradosCentigrados();
		t1.Velocidad();
		
		
	}

}



