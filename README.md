import java.util.Scanner;





public class tarea {
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
	
	public void NumeroNegativo(){
		Scanner scan= new Scanner(System.in);
		int a;
		do{		
		System.out.println("Ingresa Numero  ");
		 a = scan.nextInt();
		System.out.print(a*a+"  ");
		}while(a>0);
			System.out.print("Es numero negativo Adios");
			System.out.println("Fin Metodo Numeros negativos ");
			
					
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
	
	public void NegativosConteo(){
		Scanner scan= new Scanner(System.in);
		int a,count=0;
		do{		
		System.out.println("Ingresa Numero  ");
		 a = scan.nextInt();
		 count++;
		System.out.print(a*a+"  ");
		}while(a>0);
			System.out.print("Es numero negativo Adios Se ingresaron "+ count +"numeros");
			System.out.println("Fin Metodo Conteo ");
	}
	
	public void CienalCero(){
		for(int a=100;a>0;a-=7){
			System.out.println(a);
			
		}
		 	
		
		System.out.println("100 a 0");
	}
	
	public void PsotivoNegativo(){
		Scanner sc = new Scanner(System.in);
		int a;
		do {
			 a = sc.nextInt();
		if(a < 0)
			System.out.println("Es negativo");
		else
			System.out.println("ES positivo");
		}while(a!=0);			
		System.out.println("MEtodo Positivo negativo acabado");
	}
	
	public void Juego(){
		Scanner sc = new Scanner(System.in);
		int a,b;
		System.out.println("Introducir numero1");
		a = sc.nextInt();
		System.out.println("Introducir numero2");
		b = sc.nextInt();
		while(b!=a){
			if(b>a)
				System.out.println("Menor");
			else
				System.out.println("Mayor");
			
			System.out.println("Introducir numers");
			b = sc.nextInt();		
			
		}
		System.out.println("Ganaste");
		
	}
	
	public void Sueldos(){
		Scanner sc = new Scanner(System.in);
		double a,sueldo,sueldoMaximo=0;
		System.out.println("Numero de Sueldo");
		a = sc.nextDouble();
		for(int i=0;i<=a;i++){
			System.out.println("Sueldo");
			sueldo = sc.nextDouble();
			if(sueldo > sueldoMaximo)
				sueldoMaximo=sueldo;
			System.out.println("sueldo maximo"+ sueldoMaximo);
			
			
		}	
		
		
	}
	public  void tablas()  { 
		int a=0, b=0, c=0, d=0 ; 
		
		System.out.println ("tablas" ); 
		while (a <= 12) { 
		System.out.println ("La tabla " +a ); 
		b=1; 
		while (b <= 12) { 
		c= (a*b) ; 
		System.out.println (a+ "X" +b+ "=" +c ); 
		b++; 
		
			} 
		a++ ; 

	} 
		
} 
	public void numeritoPrimo(){
		int a,b,count;
		boolean primo;
		Scanner sc= new Scanner(System.in);
		count=0;
		System.out.println ("Intreoduce numero"); 
		b = sc.nextInt();
		for(int i=0;i<=b;i++){
			primo=true;
			a=2;
			while(a<=-1 && primo==true)
			{
				if(i%a==0)
					primo=false;
				a++;
				}
			if(primo==true){
				
				count++;
				System.out.println ("Es primo"); 
			}
			
			
			
		}
		System.out.println ("en el tango hay de 1 a "+ b + count+  "numeros primoer"); 
		
	}
	public static void main(String[]args){
		tarea t1= new tarea();
		
		//t1.NumeroNegativo();
		//t1.NegativosConteo();
		//t1.CienalCero();
		//t1.PsotivoNegativo();
		//t1.Juego();
		//t1.Sueldos();
		//t1.tablas();
		//t1.numeritoPrimo();
		
		
		
	}

}


