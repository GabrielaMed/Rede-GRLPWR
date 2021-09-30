# Rede-GRLPWR

programa
{
	
	funcao inicio()
	{
		inteiro op = 0
		cadeia local

		
		escreva ("------ R E D E    G R L P W R ------\n")
		escreva ("\n----- MENU -----\n") 
		escreva ("Pesquisar por:\n1. Local\n", "2. Dias de Promoções\n", "3. Produtos Diversos\n", "0. Sair\n")
		escreva ("\nDigite o número escolhido: \n")
		leia (op)

		enquanto (op != 0)
		{
			escolha (op)
			{
				caso 1:
				{
					limpa()

				escreva("------ R E D E   G R L P W R ------\n")
				escreva("\nLojas parceira:")
				escreva("\n1. Comper\n2. Fort\n3. Assaí\n")
				escreva("Qual opção escolhida? ")
				leia(local)
				
				 
				se (local == "1")
				{
					limpa()
					
					escreva("------ R E D E   G R L P W R ------\n")
					escreva ("\n1. COMPER\n")
					escreva ("~Produtos ~\nArroz 1KG - R$ 5,50\n", "Feijão 1KG - R$ 4,50\n", "Sal 500G - R$ 3,50\n", "Óleo 1LT - R$ 2,30\n", "Macarrão 500G - R$ 3,00\n", "Café 500G - R$ 3,75\n", "Leite 1LT - R$ 2,40\n", "Ovo 12 Unidades - R$ 11,00\n")
					pare
				}
				
				se (local == "2")
				{
					limpa()
					
					escreva("------ R E D E   G R L P W R ------\n")
					escreva("\n2. FORT\n")
					escreva("~ Produtos ~\nArroz 1KG - R$ 4,50\nFeijão 1KG - R$ 3,50\nSal 500G - R$ 2,50\nÓleo 1LT - R$ 2,00\nMacarrão 500G - R$ 2,50\nCafé 500G - R$ 3,00\nLeite 1LT - R$ 2,00\nOvo 12 Unidades - R$ 8,00\n")
           			pare
           		}
           		
           		se (local == "3")
           		{
           			limpa()
           			
           			escreva("------ R E D E   G R L P W R ------\n")
           			escreva ("\n3. ASSAÍ\n")
           			escreva ("~ Produtos ~\nArroz 1KG - R$ 5,90\n", "Feijão 1KG - R$ 3,90\n", "Sal 500G - R$ 3,50\n", "Óleo 1LT - R$ 2,50\n", "Macarrão 500G - R$ 2,75\n", "Café 500G - R$ 2,50\n", "Leite 1LT - R$ 1,80\n", "Ovo 12 Unidades - R$ 10,00\n")
                	 	pare
                	 }
			}

                	 caso 2:
                	 limpa()
                	 
                	 escreva("------ R E D E	G R L P W R ------\n")
                	 escreva ("\n~Dia de PROMOÇÕES ~\n")
                	 escreva ("\n2º SEGUNDA-FEIRA\n*Carne com 20% Desconto\nVem para o COMPER !\n")
                	 escreva ("\n4º QUARTA-FEIRA\n*Frutas e Legumes com 10% Desconto\nVem para o FORT !\n")
                	 escreva ("\n5º QUINTA-FEIRA\n*Produtos de Limpeza com 15% Desconto\nVem para o ASSAI !\n")
				pare
				
                	 caso 3:
                	 limpa()

                	 escreva("------ R E D E  G R L P W R ------\n")
                	 escreva ("\n~Produtos Diversos~\n")
                	 escreva ("1. Arroz 1KG - R$ 4,65\n")
                	 escreva ("2. Feijão 1KG - R$ 3,65\n")
                	 escreva ("3. Sal 500G - R$ 3,45\n")
                	 escreva ("4. Óleo 1LT - R$ 2,10\n")
                	 escreva ("5. Macarrão 500G - R$ 4,65\n")
                	 escreva ("6. Café 500G - R$ 3,50\n")
                	 escreva ("7. Leite 1LT - R$ 2,15\n")
                	 escreva ("8. Ovo 12 Unidades - R$ 9,50\n")

			}

			pare
		}
		
	}
}

