programa {
	
  funcao inicio() 
  {
	    
		caracter opcional
		logico   resultancia = falso
		inteiro  computar = 0 , indiceCadastro = 0
	    inteiro  nomes [15],pesquisaHospede
		
        		faca{
		            
		            escreva("Digite 1- cadastrar; 2- pesquisar; 3- sair \n ")
		            leia(opcional)
		            
		            enquanto(opcional == '1'){
		                
		                    
	                    se ( computar < 15){
	                        
	                        escreva("informe o nome do hospede: \n")
	                        leia(nomes[computar])
	                        computar++
	                    }
	                    senao{
	                        escreva("super lotado. \n")
	                    }
	                    
	                    escreva("digite 1- cadastrar; 2- pesquisar; 3-sair \n")
	                    leia(opcional)
	                     
		            }
		            
		            
        		}enquanto(opcional == '1' ou opcional == '2')
        		
        		
        		
        		
        		
        		
        		
	    }    		
        		
	}
