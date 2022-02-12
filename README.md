# 🎲 Dado-Randômico-Flowgorithm 🎲
Dado - Fluxograma

Algoritmo de um Dado (contando de 1 a 6 aleatório), feito através de fluxograma. 

Utilizado no código: 

- Laço de repetição. 
- Função random(). 

O que faz? 

Após rodar o código, o algoritmo irá escrever um valor na saída do console. 
Esse valor no caso é um número inteiro que poderar ser de 1 a 6.

- Problemática apresentada - Como a função random(6) faz a varredura de valores de 0 a 6, 
nosso dado a principio estava nos apresentando a saída do valor 0 (Zero). Logo precisamos 
tratar o código. 

- Tratamento e condição - No código temos uma condição de tratamento onde não permite sair o valor 0 (Zero).
Pois em um dado físico (cubo de 6 faces) não temos em nem uma de suas faces o valor zero, não é mesmo? 
Para tratarmos essa incoviniente situção colocamos o bloco condicional (Controle - Alternativa) com a 
condição para a variável dado igual a zero (dado == 0). 
Dessa forma enquanto a variável dado receber o valor zero (dado = 0) o laço sera verdadeiro e voltará 
para a função random(6) que por sua vez faz varredura de 0 a 6. Quando a dado receber os valores de 1 a 6, 
esse valor será escrito na tela do console. 



- Ideias de onde ultilizar o código:
Jogos RPG, Bingos...

[Link do Software Flowgorithm](www.flowgorithm.org)
Versão utilizada 2.30.3
