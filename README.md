'''
Modificar todos os exercicios condicionais para permitirem sua
execução até uma entrada do usuário desejando sair dele. Também estabeleça um número
máximo de 3 tentativas de input para quaisquer dados de entrada solicitado errados e  
informe que o programa será finalizado ao usuáio pela inobservância dos requisitos de 
entrada.

Exercícios 
1) Escreva um programa em python que leia dois números decimais, leia a operação desejada 
dentre adição, subtração, multiplicação ou divisão e mostre o seu resultado com duas casas 
decimais. Não permita a possibilidade do sistema tentar calcular uma divisão por zero ou a
leitura de caracteres que não possam ser números.

2)Escreva um programa em python para calcular os valores de imc a partir de entradas de 
dados específicos como peso e altura da pessoa. Não permita a entrada de valores que não 
possam ser números. O sistema deve trazer o resultado escrito do IMC e não o cálculo.
Não permita que o usuário entre com valores que não possam ser números
IMC = Peso[kg] ÷ (Altura²[m]) 
baixo peso < 18,5
18,5 >= peso normal < 25
25 >= pre obesidade < 30
30 >= obesidade grau 1 < 35
35 >= obesidade grau 2 < 40 
obesidade mórbida >= 40 

3) Calcule um polinômio do segundo grau através da fórmula de báskara ax²+ bx + c. Não 
permita o sistema tentar calcular divisão por zero, raiz negativa ou entrada de valores 
que não sejam números. Mostrar quantas raízes o sistema deve gerar: nenhuma(se for numero
complexo com raiz negativa, uma ou duas) e seus valores sempre com duas casas decimais.

4) O software deve permitir a leitura de um código cifrado (protocolo) que contenha 10 caracteres,
de uma estação meteorológica, a principio esse código deve trazer os seguintes dados:
zona de medição = 02 caracteres ==> 01 sul 02 norte 03 leste 04 oeste
temperatura     = 04 caracteres ==> 0321 ==> temperatura + 32,1ºC ou 1321 temperatura -32,1ºC
pluviometria    = 04 caracteres ==> 0400 ==> índice pluviométrico 400mm 
Exemplo se o código recebido for 0402980010 seu software deve decodificar a seguinte informação:
Campinas, região: Norte,  Temperatura: 29,8ºC, Índice pluviométrico:10mm 
Não permita que seja digitado um código de menos de 10 caracteres e que não seja um numero
decimal

5) Escreva um programa para aprovar  o empréstimo bancário para compra de uma casa. O programa
deve perguntar o valor da casa, o salário, e a quantidade de anos a pagar. O valor da prestação 
mensal não pode ser maior que 30% do salario. Calcule o valor da prestação como sendo o valor 
da casa dividido pelo numero de meses a pagar. Não permita o empréstimo se a condição citada 
não for atendida. 
Não permita a entrada de valores que não sejam números.

Exercicio 6 ==> Faça o usuário entrar com dois valores valor mínimo e valor máximo 
O seu algoritmo deverá decidir se a contagem que será feita é crescente ou decrescente que será mostrada ao usuário,
se o 1 º numero digitado for maior que o 2 º então a contagem é decrescente e se 
acontecer o contrário, crescente

Exercicio 7 ==> Faça um algoritmo que leia 4 números inteiros e através de uma 
rotina de repetição e decisão se consiga mostrar na tela os números organizados de forma 
crescente. Por enquanto não usar listas, conjuntos ou vetores, usar decisões e 
repetições somente pra resolver essa questão.

Exercicio 8 ==> Repita o exercício, porém agora o usuário pode escolher se
organizado de forma crescente ou decrescente

Exercicio 9 ==> Faça um contador de minutos e segundos com 02 casas decimais de
formatação se assemelhando ao mostrador de um relógio XX:XX. O programa deve durar 
1 minuto e os segundos do dia de seu aniversário. Pesquise uma forma de apagar o 
console através de comando no interpretador python para que funcione da seguinte 
forma:
00:00 ==> 1 segundo ==> apaga ==> 00:01 ==> 1 segundo ==> apaga ==> 00:02 ...


Deverá ser demonstrado ao professor 
'''
