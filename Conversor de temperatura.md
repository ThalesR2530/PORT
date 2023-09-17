funcao inicio()
	{
		real valor
		caracter temperatura 
		
		
		escreva("Digite 'f' para Fahrenheit:\n")
		escreva("Digite 'c' para Celsius: \n")
		leia(temperatura)

		escreva("Digite o valor que deseja converter:\t")
		leia(valor)
		
		escolha(temperatura){
		caso 'f':
		escreva("A conversão para graus Celsius é: ",(valor - 32)*5/9)
		pare		 
		caso 'c': 
	     escreva("A conversão para graus Fahrenheit é: ",((valor * 9/5) + 32))
	     pare
		
		}
	}
}

