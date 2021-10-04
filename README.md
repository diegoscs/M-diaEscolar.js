import java.util.Scanner;
public class MediaEscolar
{
	public static void main(String[] args)
	{
		double Nota1, Nota2, Nota3, Nota4, Media;
		String nome;
		Scanner teclado = new Scanner(System.in);

		System.out.printf("Seu nome\n");
		nome = teclado.nextLine();

		System.out.println();
		
		System.out.printf("informe um nota 1\n");
		Nota1 = teclado.nextDouble();

		System.out.printf("informe um nota 2\n");
		Nota2 = teclado.nextDouble();
		
		System.out.printf("informe um nota 3\n");
		Nota3 = teclado.nextDouble();

		System.out.printf("informe um nota 4\n");
		Nota4 = teclado.nextDouble();

			Media = (Nota1 + Nota2 + Nota3 + Nota4)/4;

			System.out.println();

				if (Media>=6)
					{
					System.out.println(nome +" \n A Media é de "+ Media + "\n Você foi aprovado");
					}
				else
					{
					System.out.println(nome +" \n A media é de "+ Media +"\n Você foi reprovado");
					}
}}
