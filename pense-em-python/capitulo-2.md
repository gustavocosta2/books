# **Capítulo 2: Variáveis, Expressões e Instruções**


## **2.10 - Exercícios**

**Exercício 2.1**
Repetindo o meu conselho do capítulo anterior, sempre que você aprender um recurso novo, você deve testá-lo no modo interativo e fazer erros de propósito para ver o que acontece. 

- Vimos que n = 42 é legal. E 42 = n? Ou x = y = 1?
  <br><br>
  **Resposta:** 42 = n não é bom, isso porque a ordem está invertida, não é possível que uma variável tenha o nome de número e muito menos realizar a atribuição dessa forma. Já o segundo caso, x = y = 1 é válido, você está atribuindo o valor de 1 para a variável y e por consequência a variável x referência o mesmo valor da variável y. 
  <br><br>
- Em algumas linguagens, cada instrução termina em um ponto e vírgula ;. O que acontece se você puser um ponto e vírgula no fim de uma instrução no Python? E se puser um ponto no fim de uma instrução?
<br><br>
**Resposta:** O Python funciona normalmente com o uso de ; no final de uma instrução mas nem sempre é uma boa prática colocá-lo, porque pode significar o fim de uma instrução *inline* e atrapalhar no restante da sentença. O ponto no final da instrução gera erro de sintaxe.
<br><br>
- Em notação matemática é possível multiplicar x e y desta forma: xy. O que acontece se você tentar fazer o mesmo no Python?
<br><br>
**Resposta:** Dá erro. É necessário especificar o uso do operador.
<br><br>

## **Exercício 2.2**
Pratique o uso do interpretador do Python como uma calculadora:

**1.** O volume de uma esfera com raio r é 4/3*pi*r^3. Qual é o volume de uma esfera com raio 5
<br><br>
**Resposta:** Se considerarmos pi como sendo aproximadamente 3,14 então o volume da esfera é: 523,33 unidades cúbicas.

**2.** Suponha que o preço de capa de um livro seja R$ 24,95, mas as livrarias recebem um desconto de 40%. O transporte custa R$ 3,00 para o primeiro exemplar e 75 centavos para cada exemplar adicional. Qual é o custo total de atacado para 60 cópias?
<br><br>
**Resposta:** $945,45 o valor total do custo para as 60 cópias.

**3.** Se eu sair da minha casa às 6:52 e correr 1 quilômetro a um certo passo (8min15s por quilômetro), então 3 quilômetros a um passo mais rápido (7min12s por quilômetro) e 1 quilômetro no mesmo passo usado em primeiro lugar, que horas chego em casa para o café da manhã?
<br><br>
**Resposta:** * Primeiro km: 7h 0min 15s
              
              * Após 4 km: 7h 21min 51s
              
              * Km final: 7h 30min 06s
