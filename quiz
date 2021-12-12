#include<stdio.h>
#include<stdlib.h>
#include <locale.h>
#include <windows.h>

int main(void)
{
	setlocale(LC_ALL, "Portuguese");
	
	HANDLE hConsole = GetStdHandle(STD_OUTPUT_HANDLE);
    CONSOLE_SCREEN_BUFFER_INFO consoleInfo;
    WORD saved_attributes;
    
    GetConsoleScreenBufferInfo(hConsole, &consoleInfo);
    saved_attributes = consoleInfo.wAttributes;
	
	int acerto=0, repete=0;
	char alter;
	
	SetConsoleTextAttribute(hConsole, FOREGROUND_GREEN);
	printf("\t======================");
	printf("\n\t-- QUIZ LINGUAGEM C--");
	printf("\n\t======================");
	SetConsoleTextAttribute(hConsole, saved_attributes);
	SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
	printf("\n\n           Seja Bem Vindo!");
	SetConsoleTextAttribute(hConsole, saved_attributes);
	printf("\n\nEste é um quiz para você se divertir e testar seus conhecimentos na linguagem C.\n");
	printf("Ele contém seis questões enumeradas de A até D, que dirão seu número de acertos no final.");
	printf("\nUse seu teclado para inserir a letra correspondente a sua resposta. Divirta-se!\n\n");
	system("pause");
	system("cls");
	
	do
	{
		printf("\nQuestao 1: Função responsável na linguagem C por imprimir algo na tela, ");
        printf("podendo ser um texto,\no conteúdo de uma variável ou constante:");
	    printf("\n\na) print\nb) scanf\nc) printf\nd) cout << ");
	    scanf(" %c",&alter);
			
	switch(alter)
	{
		case 'c':
			case 'C':
			{
				SetConsoleTextAttribute(hConsole, FOREGROUND_GREEN);
				printf("\nResposta correta! (=\n\n");
				SetConsoleTextAttribute(hConsole, saved_attributes);
				acerto++;
				repete=0;
				break;
			}
			

			
		default:
			{
				
				if((alter=='a')||(alter=='A')||(alter=='b')||(alter=='B')||(alter=='D')||(alter=='d'))
				{
					SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
					printf("\nResposta Errada. )= A alternativa correta é C.\n\n");
					SetConsoleTextAttribute(hConsole, saved_attributes);
					repete=0;
				}
				
				else
				{
				    printf("\nAlternativa não existe. Escolha uma das alternativas existentes\n\n");
				    system("pause");
	                system("cls");
				    repete=1;
				    break;
				}
				
			}
	}
	}
	
	
	
	while(repete==1);
		
	system("pause");
	system("cls");
	
	
	do
	{
	printf("\nQuestão 2: Observe o código a seguir e assinale a alternativa que descreve o caractere\nque resta para o código funcionar corretamente: \n\n");
	SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
	printf("===================================================");
	SetConsoleTextAttribute(hConsole, saved_attributes);
	SetConsoleTextAttribute(hConsole, FOREGROUND_GREEN);
	printf("\n\n   #include<stdio.h>\n\n   int main()\n   {\n      int numero;");
	printf("\n\n      printf(\"Insira um numero\");\n      scanf(\"%%d\",numero);");
	printf("\n      printf(\"O numero digitado foi %%d\",numero);\n\n      return 0;\n   }\n\n");
	SetConsoleTextAttribute(hConsole, saved_attributes);
	SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
	printf("===================================================");
	SetConsoleTextAttribute(hConsole, saved_attributes);
	
	printf("\n\na) #\nb) &\nc) ;\nd) () ");
	scanf(" %c",&alter);
	
	switch(alter)
	{
		case 'b':
			case 'B':
			{
				SetConsoleTextAttribute(hConsole, FOREGROUND_GREEN);
				printf("\nResposta correta! (=\n\n");
				SetConsoleTextAttribute(hConsole, saved_attributes);
				acerto++;
				repete=0;
				break;
			}
		default:
			{
				if((alter=='c')||(alter=='C')||(alter=='a')||(alter=='A')||(alter=='D')||(alter=='d'))
				{
					SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
				    printf("\nResposta Errada. )= A alternativa correta é B.\n\n");
				    SetConsoleTextAttribute(hConsole, saved_attributes);
					repete=0;	
			    }
			    
			    else
			    
			    {
			    	printf("\nAlternativa não existe. Escolha uma das alternativas existentes\n\n");
				    system("pause");
	                system("cls");
				    repete=1;
				}
			}
	}
			
	}
	
	while(repete==1);
	
	
	system("pause");
	system("cls");
	
	
	do
	{
	    printf("\nQuestão 3: Array Unidimensional é na linguagem C uma estrutura de dados composta por indíces,");
	    printf("que pode armazenar\numa determinada quantidade de valores do mesmo tipo. Este também pode ser chamdo de:");
	    printf("\n\na) vetor\nb) for\nc) variável\nd) constante ");
	    scanf(" %c",&alter);
	
	switch(alter)
	{
		case 'a':
			case'A':
			{
				SetConsoleTextAttribute(hConsole, FOREGROUND_GREEN);
				printf("\nResposta correta! (=\n\n");
				SetConsoleTextAttribute(hConsole, saved_attributes);
				acerto++;
				repete=0;
				break;
			}

			
		default:
			{
				if((alter=='c')||(alter=='C')||(alter=='b')||(alter=='B')||(alter=='D')||(alter=='d'))
				{
					SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
					printf("\nResposta Errada. )= A alternativa correta é A.\n\n");
					SetConsoleTextAttribute(hConsole, saved_attributes);
					repete=0;
				}
				else
				{
					printf("\nAlternativa não existe. Escolha uma das alternativas existentes\n\n");
				    system("pause");
	                system("cls");
				    repete=1;
				    break;
				}
			}
	}
			
	}
	while(repete==1);
	
	
	
	system("pause");
	system("cls");
	
	
	
	do
	{
    printf("\nQuestão 4: O que acontecerá  quando o código a seguir for compilado e executado?\n\n");
	SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
	printf("=================================\n\n");
	SetConsoleTextAttribute(hConsole, saved_attributes);
	SetConsoleTextAttribute(hConsole, FOREGROUND_GREEN);
	printf("  #include<stdio.h>\n\n  int main()");
	printf("\n  {\n\n     int fim=0;\n     while(fim>=0)\n     {\n        printf(\"%%d\",fim);\n     }\n     return 0;\n  }");
	SetConsoleTextAttribute(hConsole, saved_attributes);
	SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
	printf("\n\n=================================");
	SetConsoleTextAttribute(hConsole, saved_attributes);
	printf("\n\na) Ele exibirá o número 0 somente uma vez e finalizará o programa em seguida.");
	printf("\nb) Ele dará erro na compilação e portanto não podrerá ser executado.");
	printf("\nc) O programa não exibirá nenhum dado por causa da condicional while.");
	printf("\nd) O programa entrará em loop e exibirá o numero 0 por toda a tela e infinitamente. ");
	scanf(" %c",&alter);
	
	switch(alter)
	{
		case 'd':
			case 'D':
			{
				SetConsoleTextAttribute(hConsole, FOREGROUND_GREEN);
				printf("\nResposta correta! (=\n\n");
				SetConsoleTextAttribute(hConsole, saved_attributes);
				acerto++;
				repete=0;
				break;
			}
		default:
			{
				if((alter=='c')||(alter=='C')||(alter=='a')||(alter=='A')||(alter=='b')||(alter=='B'))
				
				{
					SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
				    printf("\nResposta Errada. )= A alternativa correta é D.\n\n");
				    SetConsoleTextAttribute(hConsole, saved_attributes);
				    repete=0;
					break;
				}
				
				else
				{
					printf("\nAlternativa não existe. Escolha uma das alternativas existentes\n\n");
				    system("pause");
	                system("cls");
				    repete=1;
				    break;
				}
				
			}
    }   
			
	}
	while(repete==1);

	
	system("pause");
	system("cls");
	
	
	do
	{
	printf("\nQuestão 5: Suponhamos que você está finalizando um programa que guardará dados de um grupo de pessoas,");
	SetConsoleTextAttribute(hConsole, FOREGROUND_GREEN);
	printf("\ne que neste programa você inseriu uma variável que perguntará e armazenará o número de pessoas que serão cadastradas.\n");
	SetConsoleTextAttribute(hConsole, saved_attributes);
	printf("Agora precisa inserir uma função de pesquisa em seu programa.\nQual será a melhor forma de fazer isso?");
	printf("\n\na) Usando a estrutura de condição 'if'.");
	printf("\nb) Através da estrutura de repetição 'for'.");
	printf("\nc) Usando a estrutura de repetição 'do while'.");
	printf("\nd) O objetivo não será atingido com nenhuma das alternativas acima. ");
	scanf(" %c",&alter);
	
	switch(alter)
	{
		case 'b':
			case 'B':
			{
				SetConsoleTextAttribute(hConsole, FOREGROUND_GREEN);
				printf("\nResposta correta! (=\n\n");
				SetConsoleTextAttribute(hConsole, saved_attributes);
				acerto++;
				repete=0;
				break;
			}
		default:
			{
				if((alter=='c')||(alter=='C')||(alter=='a')||(alter=='A')||(alter=='d')||(alter=='D'))
				
				{
					SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
				    printf("\nResposta Errada. )= A alternativa correta é B.\n\n");
				    SetConsoleTextAttribute(hConsole, saved_attributes);
					break;
				}
				else
				{
					printf("\nAlternativa não existe. Escolha uma das alternativas existentes\n\n");
				    system("pause");
	                system("cls");
				    repete=1;
				    break;
				}
				
			}
	}
			
	}
	
	while(repete==1);
	

	
	system("pause");
	system("cls");
	
	do
	{
	printf("Questão 6: Analise o código a seguir e descreva o respectivo erro:");
	SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
	printf("\n==============================================================================\n");
	SetConsoleTextAttribute(hConsole, saved_attributes);
	SetConsoleTextAttribute(hConsole, FOREGROUND_GREEN);
	printf("#include<stdio.h>\n\nint main ()\n{\n  int matriz[3][3],i;\n");
	printf("\n  printf (\"\\nDigite valor para os elementos da matriz\\n\\n\");");
	printf("\n\n  for ( i=0; i<3; i++ )\n  for ( i=0; i<3; i++ )\n  {\n    printf (\"\\nElemento[%%d][%%d] = \", i, i);");
	printf("\n    scanf (\"%%d\", &matriz[ i ][ i ]);\n  }");
	printf("\n\n  for ( i=0; i<3; i++ )\n  for ( i=0; i<3; i++ )\n  {");
	printf("\n    printf (\"\\nElemento[\%%d][\%%d] = %%d\\n\", i, i,matriz[ i ][ i ]);\n  }");
	printf("\n\n  return(0);\n}");
	SetConsoleTextAttribute(hConsole, saved_attributes);
	SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
	printf("\n==============================================================================");
	SetConsoleTextAttribute(hConsole, saved_attributes);
	printf("\na) Foi inserido uma estrutura for seguida de outra, algo que não faz sentido na linguagem C.");
	printf("\nb) No código não foi  inserida a biblioteca \"math.h\", sendo a mesma, necessária para a execução de uma matriz.");
	printf("\nc) Em uma matriz, é necessario inserir duas variáveis para indicar o indíce da linha e coluna respectivamente.");
	printf("\nd) Nenhuma das alternativas descreve o erro. ");
	scanf(" %c",&alter);
	
	switch(alter)
	{
		case 'c':
			case 'C':
			{
				SetConsoleTextAttribute(hConsole, FOREGROUND_GREEN);
				printf("\nResposta correta! (=\n\n");
				SetConsoleTextAttribute(hConsole, saved_attributes);
				acerto++;
				repete=0;
				break;
			}
		default:
			{
				if((alter=='d')||(alter=='D')||(alter=='a')||(alter=='A')||(alter=='b')||(alter=='B'))
				
				{
					SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
				    printf("\nResposta Errada. )= A alternativa correta é C.\n\n");
				    SetConsoleTextAttribute(hConsole, saved_attributes);
				    break;
					
				}
				else
				{
					printf("\nAlternativa não existe. Escolha uma das alternativas existentes\n\n");
				    system("pause");
	                system("cls");
				    repete=1;
				    break;
				}
			}
	}
		
	}
	
	while(repete==1);
	

	system("pause");
	system("cls");
	
	
	switch(acerto)
	{
		case 0:
			{
				SetConsoleTextAttribute(hConsole, FOREGROUND_RED);
				printf("\t    Poxa, você não acertou nenhuma questão. ):");
				SetConsoleTextAttribute(hConsole, saved_attributes);
                printf("\n\nMas não desanime, continue se esforçando e praticando!");
                printf("\n\n\n\t\tObrigado por participar!");
                break;
			}
		case 1:
			case 2:
				case 3:
				{
					SetConsoleTextAttribute(hConsole, FOREGROUND_INTENSITY);
					printf("\t\tPoderia ter ido melhor.");
					SetConsoleTextAttribute(hConsole, saved_attributes);
					printf("\n\nVocê acertou apenas %d questão(ões). Mas não desanime, continue se esforçando e praticando! (=",acerto);					
					printf("\n\n\n\t\tObrigado por participar!");
					break;
				}
		case 4:
			case 5:
				{
					SetConsoleTextAttribute(hConsole, FOREGROUND_GREEN);
					printf("\t\tMandou bem!");
					SetConsoleTextAttribute(hConsole, saved_attributes);
					printf("\n\nVocê acertou quase todas as questões, continue assim! (=");
					printf("\n\n\n\t\tObrigado por participar!");
					break;
				}
		
		case 6:
			{
				SetConsoleTextAttribute(hConsole, FOREGROUND_GREEN);
				printf("\tOra, ora. Parece que temos um membro do anonymous aqui!");
				SetConsoleTextAttribute(hConsole, saved_attributes);
				printf("\n\nParabéns, você acertou todas as questões. És um ótimo programador! ;) ");
				printf("\n\n\n\t\tObrigado por participar!");
				break;
			}
	}
	printf("\n\n\t\t\t\t\t\t\t\t\t\tAcertos: %d/6\n\n", acerto);
	SetConsoleTextAttribute(hConsole, FOREGROUND_INTENSITY);
	printf("\t\t\t\t\t\t\t\t\t\tQuiz Linguagem C\n\t\t\t\t\t\t\t\t\t\tversão 1.0\n\t\t\t\t\t\t\t\t\t\tDesenvolvido por Bruno\n\n");
	SetConsoleTextAttribute(hConsole, saved_attributes);
	system("pause");
	
	return 0;
}
