# Media-aluno-algoritimos
Calcula a media do aluno, feito no portugol.
//funcao do algoritimo e calcular a media aritimetica
//autor Mauricio Moraes
programa
{
	
	funcao inicio()
	{
		real nota1,nota2,nota3,nota4,media
		cadeia aluno
		escreva ("digiteo seu nome:")
		leia (aluno)
		escreva ("digite nota1:")
		leia (nota1)
		escreva("digite nota2:")
		leia (nota2)
		escreva("digite nota3:")
		leia (nota3)
		escreva("digite nota4:")
		leia (nota4)
		media = (nota1+nota2+nota3+nota4)/4
		escreva ("Sua media e:" +media)
		//verifica se a media e maior ou igual a 7
		se(media>=7) {
			escreva( "\n" + "Parabens voce foi aprovado!!!")
		}
		senao {
			escreva ("\n" + "Infelizmente voce  foi reprovado!!!")
			}
		
	}
}
