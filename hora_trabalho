package projetos_java;

import java.text.DecimalFormat;
import java.util.Scanner;

public class Valor_Servico_Trabalho {

	public static void main(String[] args) {
		// variaveis 
		double hora, custo, remuneracao, cargaHoraria;
		
		// objetos 
		Scanner teclado = new Scanner(System.in);
		DecimalFormat formatador = new DecimalFormat("#0.00");
       // entrada 
		System.out.println("Calculo do valor da hora de um serviço");
		System.out.print("Remuneração mensal esperada:");
		remuneracao = teclado.nextDouble();
		System.out.print("Custo operacional mensal:");
		custo = teclado.nextDouble();
		System.out.print("Carga Horaria Mensal de Trabalho:");
		cargaHoraria = teclado.nextDouble();
		
		//processamento 
		hora = (remuneracao + (remuneracao * 0.3) + custo + (remuneracao * 0.2)) / cargaHoraria;
		
		//saida 
		System.out.println("valor da hora: " + formatador.format(hora));
		
		teclado.close(); 
	}

}
