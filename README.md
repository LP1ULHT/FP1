**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**

*Linguagens de Programação I - 2019/2020*

# Ficha de Exercícios - 1

Na resolução destes exercícios deve ser utilizada a Linguagem de Programação C. Para além da correta implementação dos requisitos, tenha em conta os seguintes aspetos:

- O código apresentado deve ser bem indentado. 

- O código deve compilar sem erros ou *warnings* utilizando o *gcc* com as seguintes flags:

- `gcc -Wall -Wextra -Wpedantic -g exercicio1.c -o exercicio1`

- Tenha em atenção os nomes dados das variáveis, para que sejam indicadores daquilo que as mesmas vão conter.

- Evite o uso de constantes mágicas. 

- Evite duplicação de código. 

- Considere a implementação de funções para melhorar a legibilidade, evitar a duplicação e criar soluções mais genéricas.

- Deve usar a função `printf` e `scanf` para resolver exercícios.



1. Implemente um programa que escreve no ecrã a frase "O primeiro programa nunca se esquece!".

2. O que faz o seguinte programa?

   ```c
   #include <stdio.h>
   
   int main(void)
   {
   	int x;
   	scanf( "%d", &x );
   	printf("%d\n", 2*x );
   	return 0;
   }
   ```

3. Leia uma temperatura em graus Fahrenheit e apresente-a convertida em graus Celsius. A fórmula de conversão é: C = 5.0 ∗ (F − 32.0)/9.0, sendo C é a temperatura em graus Celsius e F a temperatura em graus Fahrenheit. 

2. Leia o valor do raio de um círculo. Calcule e imprima a área do círculo correspondente. A área do círculo é π ∗ raio² , considere π = 3.141592 (constante).

3. Faça um programa que peça ao utilizador 2 valores inteiros e coloque o primeiro valor numa variável chamada de A e o segundo valor noutra variável chamada de B. Em seguida, o seu programa deverá trocar o conteúdo destas variáveis e imprimir no ecrã o que cada variável contém.
   
4. Faça um programa que peça ao utilizador 4 valores inteiros. Coloque estes valores nas variáveis a, b, c, d e imprima no ecrã o resultado da seguinte expressão:(a + b + c) x d
   
5. Faça um programa que peça ao utilizador 4 notas de um aluno e imprima no ecrã a média desse aluno. 
   
8. Considere um programa com as seguintes variáveis e respetivas inicializações:

    `unsigned char c = 3.14;` 
    `unsigned short int i = 3.14; `
    `unsigned int j = ‘B’; `
    `float f = ‘C’; `

    Usando o debugger (sem recorrer a `printf()`) verifique:

    - Qual é o valor efetivo `f`?

    - Qual o valor das variáveis quando se soma o valor 2 a cada uma delas?

9. Faça um programa que, a partir da leitura  das medidas dos lados de um retângulo (comprimento e largura), lidos do teclado, calcule e imprima a área e o perímetro do retângulo.

10. Faça um programa que leia pelo teclado um valor, em euros, converta e imprima o mesmo num valor     em dólares. Considere que €1 seja equivalente a US$ 1,23.

11. A condição física de uma pessoa pode ser medida com base no cálculo do Índice de Massa Corporal     (IMC). O mesmo é calculado dividindo-se o peso desta pessoa em kg pelo quadrado da sua altura em m. Escreva um programa que leia o peso em kilograma e a altura de uma pessoa em metros, calcule e mostre o IMC. 

    *Se as entradas fossem 70.0kg para o peso e 1.80m para altura então a saída esperada seria aproximadamente 21.60.*

12. Escreva um programa que lê um certo número de segundos e dá o correspondente aos Dias, Horas, Minutos e Segundos.

     *Exemplo: 228184 segundos correspondem a 2 Dias e 15 Horas 23 Minutos e 4 Segundos.*

11. A importância de €780.000,00 será dividida entre três vencedores de um concurso. Sendo que da quantia total:

    - O primeiro vencedor receberá 46%

    - O segundo receberá 32%

    - O terceiro receberá o restante

    Calcule e imprima a quantia ganha por cada um dos vencedores.
