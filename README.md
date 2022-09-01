# calculo-de-um-ret-ngulo

package projeto_2;

import java.util.Scanner;

public class principal {

	public static void main(String[] args) {
		
        Scanner entrada = new Scanner(System.in);
        
		
		retangulo x = new retangulo();
		
		x.calculo();
		x.area();
		x.resultado();
entrada.close();
	}

}

package projeto_2;

import java.util.Scanner;

public class retangulo {
	double altura;
	double largura;
	double area;
	double perimetro;
	double resultado;
	
	Scanner entrada = new Scanner(System.in);
	
	void calculo() {
		System.out.printf("Digite o numero da altura: ");
		 altura = entrada.nextDouble();
		 System.out.printf("Digite o numero da largura: ");
		 largura = entrada.nextDouble();
	}
	
	void area() {
	area = altura*largura;
	perimetro = (2*altura) + (2*largura);
	}
	void resultado() {
		System.out.println("o perimetro é: " +  perimetro);
		System.out.println("a area é :  " +  area);
	
	
	entrada.close();
	

}
}

