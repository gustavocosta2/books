# **Cápitulo 1: A Jornada do Programa**


## **1.9 - Exercícios**


**Exercício 1.1**
<br>
É uma boa ideia ler este livro em frente a um computador para testar os exemplos durante a leitura. Sempre que estiver testando um novo recurso, você deve tentar fazer erros. Por exemplo, no programa “Hello, World!”, o que acontece se omitir 
uma das aspas? E se omitir ambas? E se você soletrar a instrução print de forma errada? Este tipo de experimento ajuda a lembrar o que foi lido; também ajuda quando você estiver programando, porque assim conhecerá o significado das mensagens de erro. É
melhor fazer erros agora e de propósito que depois e acidentalmente.

**1.** Em uma instrução print, o que acontece se você omitir um dos parênteses ou ambos?
<br><br>
**Resposta:** Caso um dos parênteses seja omitido, gerará um erro de sintaxe. Isso porque durante a execução do código em Python o interpretador não saberá lidar com esse comando .print com ausência de um ou mais parênteses.

**2.** Se estiver tentando imprimir uma string, o que acontece se omitir uma das aspas ou ambas?
<br><br> 
**Resposta:** Caso uma das aspas ou as duas sejam omitidas durante a impressão de uma string, será gerado um erro também. Caso não utilize nenhuma das duas aspas para *delimitar* a string, o erro será porque o texto escrito não é definido na
linguagem, isso significa que aquelas palavras escritas não são reservadas. Caso seja omitido apenas uma das aspas, outro erro será gerado, que é o caso onde a string não foi *delimitada* e o interpretador espera que isso seja feito, gerando
um erro de sintaxe.

**3.** Você pode usar um sinal de menos para fazer um número negativo como -2. O que acontece se puser um sinal de mais antes de um número? E se escrever assim: 2++2?
<br><br>
**Resposta:**  Ele fará a distribuição de sinais. No exemplo dado, 2++2 será aplicado a Regra de Sinais da matemática, + com + resultará em +. A mesma coisa para 2--2, resultará em +4.
iss
**4.** Na notação matemática, zeros à esquerda são aceitáveis, como em 02. O que acontece se você tentar usar isso no Python?
<br><br>
**Resposta:** É gerado um erro de sintaxe, isso porque em Python sendo uma linguagem formal, começar um número com 0 à esquerda deixa a informação com uma possível *ambiguidade*, isso porque iniciando com zero à esquerda ele pode pertencer a
diferentes sistemas númericos como o hexadecimal, binário.

**5.** O que acontece se você tiver dois valores sem nenhum operador entre eles?
<br><br>
**Resposta:** É gerado um erro de sintaxe.

## **Exercício 1.2**
Inicialize o interpretador do Python e use-o como uma calculadora. <br><br>
**1.** Quantos segundos há em 42 minutos e 42 segundos?
<br><br>
**Resposta:** 2562 segundos.

**2.** Quantas milhas há em 10 quilômetros? Dica: uma milha equivale a 1,61 quilômetro.
<br><br>
**Resposta:** Aproximadamente 6,2 milhas.

**3.** Se você correr 10 quilômetros em 42 minutos e 42 segundos, qual é o seu passo médio (tempo por milha em minutos e segundos)? Qual é a sua velocidade média em milhas por hora?
<br><br>
**Resposta:** 

-> Passo médio (Tempo por Milha): 6 minutos e 52 segundos.<br>
-> Velocidade média (milhas/hora): 8,73 milhas por hora.
