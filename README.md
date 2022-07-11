# EstruturaDeDados1





                              *******Lista encadeada Simples*******
                              
                              
Link replit --> https://replit.com/@CrislleyPborga/ListaEncadeadaCrislley#main.c   


                              *******Lista encadeada Dupla*******
                              
Link replit --> https://replit.com/@CrislleyPborga/ListaEncadeadaDupla20      

                              *******Lista de exercicios sobre filas*******
    
                              
Exercicio 1 -->  https://replit.com/@CrislleyPborga/Exercicio1Fila#main.c

Exercícios 2 e 3 --> https://replit.com/@CrislleyPborga/Exercicio2Fila#main.c


                          ******Lista de exercicios sobre pilhas**********
                          
Exercicio 1 --> https://replit.com/@CrislleyPborga/ExercicioPilha#main.c



                        **** Seminário  *****
                        
Link --> https://www.canva.com/design/DAFCyUja6j0/nPbeUw-kes_2A2AuhfgbAQ/edit?utm_content=DAFCyUja6j0&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

Trabalho Final código--> https://replit.com/@CrislleyPborga/TrabFinalEd1#main.c
#  	Descrição geral do trabalho
Este trabalho, que foi realizado em linguagem de programação C, tem como objetivo dividir e armazenar mais de 100 mil nomes em uma tabela de espalhamento(Tabela Hash), ela é desenvolvida usando lista encadeada dupla e segue todos os requisitos solicitados pelo docente. Ela é composta por 53 chaves ou no caso 53 listas encadeadas dentro de outra lista encadeada. O trabalho contém também o método de ordenação QuickSort o mesmo baseia-se na ordenação em sucessivas repartições(separações).         	
#   Alguns métodos do trabalho
#   ListaHash *criaListaHash(); 
		Este método aloca a memória para a tabela hash e para as listas de cada chave 
#  void removerElementoHash();
		Este método verifica se o nodo/nome está na tabela se estiver ele chama a função da lista encadeada dupla  e faz a remoção;
#  void insereElementoHash();
		Este método verifica em qual lista o nome será adicionado e após isso chama a função insere da lista encadeada dupla e passa como parâmetro o nome e a lista;
#  void criaHash();
		Este método cria a tabela hash;
#   void quickSort();
		Método responsável pelo quickSort
#   void ordenaLista();
		Este método é responsável por ordenar de ordem alfabética a lista que passa por parâmetro;
#   void percorreListaHash()
		Este método é responsável por “achar” a lista que deve ser percorrida e após isso chama o método da lista encadeada dupla para percorrer a lista(Listar todos os elementos)
      

# 3.   Considerações Finais
	O gráfico abaixo representa a quantidade de elementos por chave, no trabalho temos 53 chaves e nela temos uma 
	média de 1901.66037736 nomes por tabela
	Link para o grafico --> https://drive.google.com/file/d/1fdkuvZg_qXdzGpPjBGRrY4ZxLSRX4EIc/view?usp=sharing
	<img src="https://user-images.githubusercontent.com/47753376/178259694-10ed1cc5-d052-446f-9f33-42d761ff8b02.png">

  

	A distribuição da quantidade de elementos por chave pode ser aproximada com uma distribuição 
	normal com desvio padrão de 45.1822069655.
	Este trabalho foi uma ótima maneira de aprender a tabela hash, pois pude aproveitar vários 
	métodos da lista encadeada dupla e aprimorar para a tabela hash, fazendo com que ficasse mais 
	fácil a realização do mesmo. 
	
	No arquivo nomes.txt tem todos os nomes que devem ser adicionado para fazer o upload para 
	a lista hash, e o dados.txt é o responsável pelos dados de quantos nomes estão em cada chave;
	
	


              
