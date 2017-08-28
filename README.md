import java.util.Scanner;






public class tarea {
	
	
	
	public void Holamundo(){
		
		
		System.out.println("Hola mundo");
	}
	public void Series(){
		for(int i =0;i<101;i++){
			System.out.print(" ,"+i);			
		}
		for(int i =101;i!=0;i--){
			
		System.out.print(" ,"+i);			
		}
		for(int i=100;i<1000;i+=2){
			
			System.out.print(","+i);
		}
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
	
	public void Serie(){
		for(int a=0;a<=9;a++){
			for(int b=0;b<=9;b++){
				for(int c=0;c<=9;c++){
					for(int d=0;d<=9;d++){
						for(int e=0;e<=9;e++){
							if(a==3)
								System.out.print("E");
							else
								System.out.print(a);
							if(b==3)
								System.out.print("E");
							else
								System.out.print(b);
							if(c==3)
								System.out.print("E");
							else
								System.out.print(c);
							if(d==3)
								System.out.print("E");
							else
								System.out.print(d);
							if(e==3)
								System.out.print("E");
							else
								System.out.println(e);
							System.out.println("   ");
													
						}
						
					}
					
				}
				
			}
			
		}
		
		
	}
	
	public void Vectores(){
		int array[]= new int[5];
		Scanner sc= new Scanner(System.in);
		for(int i=0;i<5;i++){
			System.out.println("Escribir numero");
			array[i] = sc.nextInt();
			System.out.println(array[0]+" "+array[1]+" "+array[2]+" "+array[3]+" "+array[4]);
		}
		
		
	}
	public void Vectores1(){
		int array[]= new int[5];
		Scanner sc = new Scanner(System.in);
		int sum1=0,sum2=0,count1=0,count2=0,count3=0;
		  for(int i=0;i<5;i++){
			  System.out.println("Introduccir numero");
			  int a=sc.nextInt();
			  		  
		  }
		  for(int i=0;i<5;i++){
			  if(array[i]==0)
				  count3++;
			  else{
				  if(array[i]>0){
					  sum1=sum1+array[i];
					  count1++;					  
				  }
				  else{
					  sum2=sum2+array[i];
					  count2++;
					  
				  }
			  }
			  
			  if(count1==0)
				  System.out.println("no promedio numeros pos");
			  else
				  System.out.println(" prmedio numeros pos"+ sum1/count1);
			  if (count2==0)
			  System.out.println("no promedio numeros negativos");
			  else
				  System.out.println(" promedio numeros negativos"+sum2/count2);
			 
				  System.out.println("Cantidad e cero"+count3);
		  }
		 
			  
		
		
	}
	
	public void Vectores2(){
		Scanner sc= new Scanner(System.in);
		int array[]= new int[5];
		
		
		
	}
	
	public void Vectores3(){
		int array[] = new int[5];
		Scanner sc= new Scanner(System.in);
		for(int i =0;i<5;i++){
			System.out.print("Meter numer");
			array[i]= sc.nextInt();
			}
		System.out.print("inversa");
		for(int i =4;i>=0;i--){
			System.out.print(array[i]);
			
		}
		
		
		
	}
	public void Vectores4(){
		int i, array[];
		Scanner sc= new Scanner(System.in);
		array = new int[10];
		for( i=0;i<10;i++){
			System.out.println("numero:  ");
			array[i]=sc.nextInt();			
		}
		for(i=0;i<=4;i++){
			System.out.println(array[i]);
			System.out.println(array[9-i]);
			
		}		
		
	}
	public void VectoresBi(){
		int array[][] = new int[5][5];
		for(int i =0;i<5;i++){
			for(int j=0;j<5;j++){
				array[i][j]=i+j;
				
			}
			
		}
		for(int i=4;i>=0;i--){
			for(int j=0;j<5;j++){
				System.out.println(array[i][j]);
				
			}
		}
		
	}
	
	public void VectoresBi1(){
		
		int [][] valores = {{1, 2, 3}, 
				           {3 , 2 , 1}, 
				           {5, 4, 2}};

		int suma_colu = 0, suma_fila = 0;		



				for(byte i = 0;i < valores.length;i++){
					
					for(byte j = 0; j < valores.length;j++){
						
						suma_colu += valores[i][j];
					}
					
					
				}
				
			for(byte j = 0;j < valores.length;j++){
					
					for(byte i = 0; i < valores.length;i++){
						
						suma_fila += valores[i][j];
				System.out.println("valores [" + i +"][" + j + "] = " + valores[i][j]);
					
					}
				}
				
			System.out.println(null+ "Suma de columnas : " + suma_colu);
			System.out.println(null+ "Suma de filas : " + suma_fila);	
			}
	
	public void VectoresBi2(){
		int[][] va1 = new int [3][3];
		int[][] va2 = new int [3][3];
	int[][] suma = new int [3][3];
		for(byte i = 0; i < va1.length;i++){
			for(byte j = 0; j < va1[i].length;j++){
				va1[i][j] = (int) (Math.random() * 98);
				va2[i][j] = (int) (Math.random() * 98);
				suma[i][j] = va1[i][j] + va2[i][j];
		System.out.print("va1[" + i + "][" + j + "] = " + va1[i][j]);
		System.out.print("va2[" + i + "][" + j + "] = " + va2[i][j]);
		System.out.print("suma[" + i + "][" + j + "] = " + suma[i][j]);
			}

		}
		
	}
	
	public tarea(){
		
		System.out.println();
		
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
		//t1.Serie();
		//t1.Vectores();
		//t1.Vectores1();
		//t1.Vectores3();
		//t1.Vectores4();
		//t1.VectoresBi();
		//t1.VectoresBi1();
		//t1.VectoresBi2();
		//t1.Holamundo();
		//t1.Series();
	}

}
