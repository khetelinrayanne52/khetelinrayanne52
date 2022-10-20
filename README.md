Questão 1

#include <stdio.h>
#include <stdlib.h>
/*. Faça um programa que leia um número inteiro e o imprima, então leia um número real e
também o imprima. */

int main() {
    int a = 10;
    printf("Numero inteiro %d ",a);
    printf("\n");
    float b = 3.50;
    printf("Numero real %.2f ",b);
    printf("\n\n\n");
    system("pause");
    return 0;
}

Questão 3

#include <stdio.h>
#include <stdlib.h>
/* Peça ao usuário para digitar três valores inteiros e imprima a soma deles */

int main() {
    int num1, num2, num3, soma;
    printf("Insira o primeiro valor: ");
    scanf("%d", &num1);
    printf("Insira o segundo valor: ");
    scanf("%d", &num2);
    printf("Insira o terceiro valor: ");
    scanf("%d", &num3);
    soma = num1 + num2 + num3;
    printf("soma = %d", soma);
    printf("\n\n");
    system("pause");
    return 0;
}
  
Questão 5
 
#include <stdio.h>
#include <stdlib.h>
/* Peça ao usuário para digitar três valores inteiros e imprima a soma deles */

int main() {
    int num1, num2, num3, soma;
    printf("Insira o primeiro valor: ");
    scanf("%d", &num1);
    printf("Insira o segundo valor: ");
    scanf("%d", &num2);
    printf("Insira o terceiro valor: ");
    scanf("%d", &num3);
    soma = num1 + num2 + num3;
    printf("soma = %d", soma);
    printf("\n\n");
    system("pause");
    return 0;
}
 
Questão 6

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/*Ler uma temperatura em graus Celsius e apresentá-la convertida em graus Fahrenheit. A
fórmula de conversão é: 𝐹 = 𝐶 ∗ (9,05,0) + 32,0, sendo 𝐹 a temperatura em Fahrenheit e 𝐶 a
temperatura em Celsius*/

int main() {
    float c, f;
    printf("Digite a temperatura em Graus Celsius: ");
    scanf("%f", &c);
    f = c*(9.0/5.0) + 32.0;
    printf("\nA temperatura em Fahrenheit eh: %.2f", f);
    return 0;
}
 
Questão 8

<stdio.h>
#include <stdlib.h>
#include <math.h>
/* Ler uma temperatura em graus Kelvin e apresentá-la convertida em graus Celsius. A
fórmula de conversão é: 𝐶 = 𝐾 − 273,15, sendo 𝐶 a temperatura em Celsius e 𝐾 a
temperatura em Kelvin*/

int main()
{
    float k, c;
    printf("Digite a temperatura em Graus Kelvin: ");
    scanf("%.2f", &k);
    c = k - 273.15;
    printf("A temperatura em Celsius eh: %.2f", c);
    return 0
}

Questão 9
 
#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/* . Ler uma temperatura em graus Celsius e apresentá-la convertida em graus Kelvin. A
fórmula de conversão é: 𝐾 = 𝐶 + 273,15, sendo 𝐶 a temperatura em Celsius e 𝐾
atemperatura em Kelvin*/

int main() {
    float c, k;
    printf("Digite a temperatura em Graus Celsius: ");
    scanf("%f", &c);
    k= c + 273.15;
    printf("\nA temperatura em Kelvin eh: %.2f", k);
    return 0;
{

Questão 11

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/* Ler uma velocidade em 𝑚/𝑠 (metros por segundo) e apresentá-la convertida em
𝐾𝑚/ℎ (quilômetros por hora). A fórmula de conversão é: 𝐾 = 𝑀 ∗ 3,6 , sendo 𝐾 a velocidade
em 𝑘𝑚/ℎ e 𝑀 em 𝑚/𝑠. */

int main() {
    float ms, kmh;
    printf("Digite a velocidade em m/s: ");
    scanf("%f", &ms);
    kmh = ms *3.6;
    printf("\nA velocidade convertida em km/h eh: %.2f", kmh);
    return 0;
}

Questão 12
 
#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/* Ler uma distância em milhas e apresentá-la convertida em quilômetros. A fórmula de
conversão é: 𝐾 = 1,61 ∗ 𝑀 , sendo 𝐾 a distância em quilômetros e 𝑀 em milhas  */

int main() {
    float milhas, km;
    printf("Digite a distancia em milhas: ");
    scanf("%f", &milhas);
    km = 1.61 * milhas;
    printf("\nA distancia convertida em milhas: %.2f", km);
    return 0;
}

Questão 13.

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/*  Ler uma distância em quilômetros e apresentá-la convertida em milhas. A fórmula de
conversão é: 𝑀 = 𝐾/1,61 , sendo 𝐾 a distância em quilômetros e 𝑀 em milhas */

int main() {
    float km, milhas;
    printf("Digite a distancia em milhas: ");
    scanf("%f", &km);
    milhas = km / 1.61;
    printf("\nA velocidade convertida em milhas eh: %.2f", milhas);
    return 0;
}




Questão 14

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/*  Ler um ângulo em graus e apresentá-lo convertido em radianos. A fórmula de conversão é:
𝑅 = 𝐺 ∗ 𝜋/180 , sendo 𝐺 o ângulo em graus e R em radianos e 𝜋 = 3,141592 */
int main() {
    const double pi = 3.14;
    float graus, r;
    printf("Digite o valor do angulo em graus: ");
    scanf("%f", &graus);
    r = graus * pi/180;
    printf("\nO angulo convertido em radianos eh: %.2f", r);
    return 0;
}

Questão 15

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/* Ler um ângulo em radianos e apresentá-lo convertido em graus. A fórmula de conversão é:
𝐺 = 𝑅 ∗ 180/𝜋 , sendo 𝐺 o ângulo em graus e 𝑅 em radianos e 𝜋 = 3,141592.  */

int main() {
    const double pi = 3.14;
    float graus, r;
    printf("Digite o valor do angulo em radianos: ");
    scanf("%f", &r);
    graus = r * 180/pi;
    printf("\nO angulo convertido em graus eh: %.2f", graus);
    return 0;
}

Questão 16
 
#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/*  Ler um valor de comprimento em polegadas e apresentá-lo convertido em centímetros. A
fórmula de conversão é: 𝐶 = 𝑃 ∗ 2,54 , sendo 𝐶 o comprimento em centímetros e 𝑃 o
comprimento em polegadas.*/

int main() {
    float p, c;
    printf("Digite o valor em polegadas: ");
    scanf("%f", &p);
    c = p * 2.54;
    printf("\nO valor convertido em centimetros eh: %.2fcm", c);
    return 0;
}
Questão 17

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/*  Ler um valor de comprimento em centímetros e apresentá-lo convertido em polegadas. A
fórmula de conversão é: 𝑃 = 𝐶/2,54 , sendo 𝐶 o comprimento em centímetros e 𝑃 o
comprimento em polegadas..*/

int main() {
    float p, c;
    printf("Digite o valor em centimetros: ");
    scanf("%f", &c);
    p = c / 2.54;
    printf("\nO valor convertido em polegadas eh: %.2f", p);
    return 0;
}

Questão 18

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/* Ler um valor de volume em metros cúbicos 𝑚³ e apresentá-lo convertido em litros. A
fórmula de conversão é: 𝐿 = 1000 ∗ 𝑀, sendo 𝐿 o volume em litros e 𝑀 o volume em metros
cúbicos*/

int main() {
    float mc, lt;
    printf("Digite o volume em m3: ");
    scanf("%f", &mc);
    lt = 1000 * mc;
    printf("\nO valor convertido em litros eh: %.2f", lt);
    return 0;
}

Questão 19

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/* Ler um valor de volume em metros cúbicos 𝑚³ e apresentá-lo convertido em litros. A
fórmula de conversão é: 𝐿 = 1000 ∗ 𝑀, sendo 𝐿 o volume em litros e 𝑀 o volume em metros
cúbicos*/

int main() {
    float mc, lt;
    printf("Digite o volume em m3: ");
    scanf("%f", &mc);
    lt = 1000 * mc;
    printf("\nO valor convertido em litros eh: %.2f", lt);
    return 0;
}

Questão 20

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/*   Ler um valor de massa em quilogramas e apresentá-lo convertido em libras. A fórmula de
conversão é: 𝐿 = 𝐾/0,45 , sendo 𝐾 a massa em quilogramas e 𝐿 a massa em libras */

int main() {
    float kg, lb;
    printf("Digite massa em kg: ");
    scanf("%f", &kg);
    lb = kg /0.45;
    printf("\nO valor convertido em libras: %.2f",lb);
    return 0;
}

Questão 22

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/* Ler um valor de comprimento em jardas e apresentá-lo convertido em metros. A fórmula
de conversão é: 𝑀 = 0,91 ∗ 𝐽 , sendo 𝐽 o comprimento em jardas e 𝑀 o comprimento em
metros.  */

int main() {
    float jd, mt ;
    printf("Digite o comprimento em jardas: ");
    scanf("%f", &jd);
    mt = 0.91 * jd;
    printf("\nO comprimento convertido em metros: %.2f",mt);
    return 0;
}

Questão 23

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/*  Ler um valor de comprimento em metros e apresentá-lo convertido em jardas. A fórmula
de conversão é: 𝐽 = 𝑀/0,91 , sendo 𝐽 o comprimento em jardas e 𝑀 o comprimento em
metros  */

int main() {
    float jd, mt ;
    printf("Digite o comprimento em metros: ");
    scanf("%f", &mt);
    jd = mt /0.91;
    printf("\nO comprimento convertido em jardas: %.2f",jd);
    return 0;
}

Questão 24
 
#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/*  Ler um valor de área em metros quadrados 𝑚2e apresentá-lo convertido em acres. A
fórmula de conversão é: 𝐴 = 𝑀 ∗ 0,000247, sendo 𝑀 a área em metros quadrados e 𝐴 a área
em acres  */

int main() {
    float m2, ac;
    printf("Digite a area em m2: ");
    scanf("%f", &m2);
    ac = m2 * 0.000247;
    printf("\nA area em acres eh: %.2f",ac);
    return 0;
}

Questão 28

#include <stdio.h>
#include <stdlib.h>
/*  Efetue a leitura de três valores e apresente como resultado a soma dos quadrados dos três
valores lidos */

int main() {
    int num1 = 6;
    int num2 = 3;
    int num3 = 9;
    printf("Numero 1: %d " , num1);
    printf("\nNumero 2: %d " , num2);
    printf("\nNumero 3: %d" , num3);
    printf("\nA soma dos quadrados dos numeros lidos e = %d", num1*num1 + num2*num2 + num3*num3);
    printf("\n\n");
    system("pause");
    return 0;
}

Questão 29
 
#include <stdio.h>
#include <stdlib.h>

// Leia quatro notas, calcule a média aritmética e imprima o resultado

int main() {
    float nota1 = 9.0;
    printf("Nota 1: %.1f", nota1);
    float nota2 = 8.5;
    printf("\nNota 2: %.1f ", nota2);
    float nota3 = 7.0;
    printf("\nNota 3: %.1f ", nota3);
    float nota4 = 6.5;
    printf("\nNota 4: %.1f ", nota4);
    printf("\nA media aritmetica das notas e = %.1f", nota1 + nota2 + nota3 + nota4 / 4);
    printf("\n\n");
    system("pause");
    return 0;
}

Questão 31
#include <stdio.h>
#include <stdlib.h>

// Leia um número inteiro e imprima o seu antecessor e o seu sucessor


int main() {
    int num = 5;
    printf("Numero inteiro: %d" , num);
    printf("\nAntecessor do numero: %d ",num - 1);
    printf("\nSucessor do numero: %d ",num + 1);
    printf("\n\n");
    system("pause");
    return 0;
}


Questão 32

#include <stdio.h>
#include <stdlib.h>

/* Leia um número inteiro e imprima a soma do sucessor de seu triplo com o antecessor de seu
dobro */


int main() {
    int num = 5;
    printf("Numero inteiro: %d" , num);
    printf("\nSoma do do sucessor de seu triplo com o antecessor de seu dobro : %d ", num * 3 + 1 + num * 2 -1);
    printf("\n\n");
    system("pause");
    return 0;
}
 
Questão 34

#include <stdio.h>
#include <stdlib.h>

/* Leia o valor do raio de um círculo e calcule a área do círculo correspondente. Imprima o
resultado dessa operação. A área do círculo é 𝜋 ∗ 𝑟𝑎𝑖𝑜², considere 𝜋 = 3,141592 */


int main() {
    int raio = 12;
    float raioquadrado = raio * raio;
    printf("O valor do raio do circulo e:%d" , raio);
    printf("\nA area do circulo e: %.2f " , 3.14* raioquadrado);
    printf("\n\n");
    system("pause");
    return 0;
}

Questão 35

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/* Sejam 𝑎 e 𝑏 os catetos de um triângulo, onde a hipotenusa é obtida pela equação:
ℎ𝑖𝑝𝑜𝑡𝑒𝑛𝑢𝑠𝑎 = √𝑎2 + 𝑏2. Faça um programa que receba os valores de 𝑎 e 𝑏 e encontre o
valor da hipotenusa através da equação. Imprima no final o resultado dessa operação. */

int main() {
    int num1, num2, num3;
    float hipotenusa;
    printf("Insira o primeiro valor: ");
    scanf("%d", &num1);
    printf("Insira o segundo valor: ");
    scanf("%d", &num2);
    hipotenusa = sqrt((num1* num1) + (num2* num2));
    printf("A hipotenusa dos valores eh = %.2f", hipotenusa);
    printf("\n\n");
    system("pause");
    return 0;
}

Questão 36

#include <stdio.h>
#include <stdlib.h>
/* . Leia a altura e o raio de um cilindro circular e imprima o volume do cilindro. O volume de
um cilindro circular é calculado por meio da seguinte fórmula: V = 𝜋 ∗ 𝑟𝑎𝑖𝑜2∗ 𝑎𝑙𝑡𝑢𝑟𝑎, onde𝜋 = 3,141592 .*/

int main() {
    int altura = 4;
    printf("A altura do cilindro eh: 4");
    int raio = 2;
    printf("\nO raio do cilindro eh: 2");
    float volume = 3.14 * (raio*raio) * altura;
    printf("\nO volume do cilindro eh: %.2f" , volume);
    printf("\n\n");
    system("pause");
    return 0;
}

Questão 37

#include <stdio.h>
#include <stdlib.h>
/* Faça um programa que possa entrar com o valor de um produto e imprima o valor tendo
em vista que o desconto foi de 12% */

int main() {
    float valor, desconto, vfinal;
    printf("Digite o preco do produto:");
    scanf("%f" , &valor);
    desconto =  valor * 0.12;
    vfinal = valor - desconto;
    printf("\nO valor com desconto eh: %.2f" ,vfinal);


    printf("\n\n");
    system("pause");
    return 0;
}
Questão 39

#include <stdio.h>
#include <stdlib.h>
/* A importância de R$ 780.000,00 será dividida entre três ganhadores de um concurso.
Sendo que da quantia total:
 O primeiro ganhador receberá 46%;
 O segundo receberá 32%;
 O terceiro receberá o restante;
Calcule e imprima a quantia ganha por cada um dos ganhadores. */

int main() {
    float valor = 780.000;
    printf("O valor total eh:R$%.3f", valor );
    float gan1, gan2, desc2, gan3, desc3;
    gan1=  valor * 0.46;
    printf("\nPrimeiro ganhador recebe:R$%.3f", gan1);
    gan2=  valor * 0.32;
    printf("\nPrimeiro ganhador recebe:R$%.3f", gan2);
    gan3=  valor * 0.22;
    printf("\nPrimeiro ganhador recebe:R$%.3f", gan3);
    printf("\n\n");
    system("pause");
    return 0;
}

Questão 40

#include <stdio.h>
#include <stdlib.h>
/* Uma empresa contrata um encanador a R$ 30,00 por dia. Crie um programa que solicite o
número de dias trabalhados pelo encanador e imprima a quantia líquida que deverá ser paga,
sabendo-se que são descontados 8% para imposto de renda.
*/

int main() {
    float dias;
    printf("\nQuantos dias o encanador trabalhou? ");
    scanf("%f" , &dias);
    float sal = 30.00;
    float ir, salfinal;
    ir = sal * 0.08;
    salfinal = sal - ir;
    printf("\nO encanador recebera: R$%.2f" , salfinal * dias);
    printf("\n\n");
    system("pause");
    return 0;
}

Questão 41

#include <stdio.h>
#include <stdlib.h>
/*  Faça um programa que leia o valor da hora de trabalho (em reais) e número de horas
trabalhadas no mês, e imprima o valor a ser pago ao funcionário, adicionando 10% sobre o
valor calculado */

int main() {
    float horadia = 5.50;
    printf("Voce recebe por hora: R$%.2f", horadia);
    float horames;
    printf("\nQuantas horas voce trabalhou esse mes: ");
    scanf("%f", &horames);
    float hrstrab = horadia * horames;
    float bonus, salfim;
    bonus = hrstrab * 0.10;
    salfim = hrstrab + bonus;
    printf("Voce recebera esse mes: R$%.2f", salfim);
    printf("\n\n");
    system("pause");
    return 0;
}

Questão 42

#include <stdio.h>
#include <stdlib.h>
/* Receba o salário-base de um funcionário, calcule e imprima o salário a receber, sabendo-se
que esse funcionário tem uma gratificação de 5% sobre o salário-base. Além disso, paga % de
imposto sobre o salário-base
*/
int main() {
    float salb;
    printf("Insira seu salario: R$");
    scanf("%f", salb);
    float gratificacao, imposto, saltot;
    gratificacao = salb * 0.05;
    imposto = salb * 0.07;
    saltot = salb + gratificacao - imposto;
    printf("\nSalario a receber eh: R$%.2f", saltot);
    printf("\n\n");
    system("pause");
    return 0;
}

Questão 43 

#include <stdio.h>
#include <stdlib.h>

/* Escreva um algoritmo para criar um programa de ajuda para vendedores. A partir de um
valor total lido, mostre:
 O total a pagar com desconto de 10%;
 O valor de cada parcela, no parcelamento de 3 x sem juros;
 A comissão do vendedor, no caso de a venda ser a vista (5% sobre o valor com desconto)
 A comissão do vendedor, no caso de a venda ser parcelada (5% sobre o valor total)
*/
int main() {
    float vlrtot;

    printf("Qual o valor total? ");
    scanf("%f", &vlrtot);

    float des10, vlrapagar;
    des10 = vlrtot * 0.10;
    vlrapagar = vlrtot - des10;
    printf("\nTotal a pagar com desconto de 10%: R$%.2f" , vlrapagar);
    float parc3;
    parc3= vlrtot / 3;
    printf("\nTotal do parcelamento em 3x sem juros: R$%.2f", parc3);
    float comissao;
    comissao= vlrapagar * 0.05;
    printf("\nComissao venda a vista: R$%.2f", comissao);
    float comissao2;
    comissao2= vlrtot * 0.05;
    printf("\nComissao venda parcelada: R$%.2f", comissao2);
    printf("\n\n");
    system("pause");
    return 0;
}
 
Questão 47. 

#include <stdio.h>
#include <stdlib.h>
#include <string.h>
// Leia um número inteiro de 4 dígitos e imprima 1 dígito por linha

int main() {
   int num1 = 1 , num2 = 2 , num3 = 3 , num4 = 4;
   printf("Numero inteiro de 4 digitos : %d%d%d%d " , num1, num2, num3, num4);
   printf("\n%d\n%d\n%d\n%d\n", num1, num2, num3);
   system("pause");
   return 0;
}

Questão 48

#include <stdio.h>
#include <stdlib.h>
// Leia um valor inteiro em segundos, e imprima-o em horas, minutos e segundos

int main() {
   int horas, minutos, segundos;
   printf("Digite os segundos: ");
   scanf("%d" , &segundos);
   horas = segundos / 3600;
   minutos = (segundos -(horas*3600))/60;
   segundos = segundos - (horas*3600)-(minutos*60);
   printf("%dh: %dm: %ds: ", horas, minutos, segundos);
   printf("\n");
   system("pause");
   return 0;
}
Questão 49
 
#include <stdio.h>
#include <stdlib.h>
/* Faça um programa para leia o horário (hora, minuto e segundo) de início e a duração, em
segundos, de uma experiência biológica. O programa deve resultar com o novo horário (hora,
minuto e segundo) do termino da mesma. */

int main() {
   int h= 15, m =30, s=10;
   printf("A hora inicial eh: %d:%d:%d", h, m, s);
   int duracao = 10800;
   printf("\nA hora de duracao da experiencia em segundos eh: %d", duracao);
   int horas, minutos, segundos;
   horas = duracao / 3600;
   minutos = (duracao-(horas*3600))/60;
   segundos = duracao - (horas*3600)-(minutos*60);
   int hf, mf, sf;
   hf= h + horas;
   mf= m + minutos;
   sf= s + segundos;
   printf("\nA experiencia terminara as: %d:%d:%d", hf, mf, sf );

   printf("\n");
   system("pause");
   return 0;
}

Questão 50

#include <stdio.h>
#include <stdlib.h>
/* Implemente um programa em C que calcule o ano de nascimento de uma pessoa a partir
de sua idade e do ano atual */

int main() {
    int idade, ano_atual, ano_nasc;
    printf("Digite sua idade: ");
    scanf("%d", &idade);
    printf("Insira em que ano estamos: ");
    scanf("%d", &ano_atual);
    ano_nasc = ano_atual - idade;
    printf("Voce nasceu em: %d", ano_nasc);
    printf("\n");
    system("pause");
    return 0;
}
Questão 52

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/* Três amigos jogaram na loteria. Caso eles ganhem, o prêmio deve ser repartido
proporcionalmente ao valor que cada deu para a realização da aposta. Faça um programa que
lê quanto cada apostador investiu, lê o valor do prêmio, e escreve quanto cada um ganharia.
*/

int main() {
    float amg1, amg2, amg3, vlrarrecadado;
    printf("\nValor aposta amigo 1: ");
    scanf("%f", &amg1);
    printf("\nValor aposta amigo 2: ");
    scanf("%f", &amg2);
    printf("\nValor aposta amigo 3: ");
    scanf("%f", &amg3);
    vlrarrecadado = amg1 + amg2 + amg3;
    printf("\nValor arrecadado para aposta: %.2f" , vlrarrecadado);
    float premio = 980.000;
    printf("\nO valor do premio eh: %.3f" , premio);
    float pct1, pct2, pct3;
    pct1 = (amg1 * 100)/vlrarrecadado;
    pct2 = (amg2 * 100)/vlrarrecadado;
    pct3 = (amg3 * 100)/vlrarrecadado;
    printf("\nAmigo 1 apostou: %.2f porcento do total arrecadado.", pct1);
    printf("\nAmigo 2 apostou: %.2f porcento do total arrecadado.", pct2);
    printf("\nAmigo 3 apostou: %.2f porcento do total arrecadado.", pct3);
    printf("\nAmigo 1 recebera: R$%.2f.", premio * pct1/100);
    printf("\nAmigo 2 recebera: R$%.2f.", premio * pct2/100);
    printf("\nAmigo 3 recebera: R$%.2f.", premio * pct3/100);
    return 0;
}

Questão 53.

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/*  Faça um programa para ler as dimensões de um terreno (comprimento 𝑐 e largura 𝑙), bem
como o preço do metro do arame 𝑝, então fornecer como saída o custo para cercar este
mesmo terreno*/

int main() {
    float largura, comprimento, preco, total;
    printf("\nQual a largura do terreno: ");
    scanf("%f", &largura);
    printf("\nQual o comprimento do terreno: ");
    scanf("%f", &comprimento);
    printf("\nQual o preco do terreno: R$");
    scanf("%f", &preco);
    total = (comprimento * largura * preco);
    printf("\nVoce gastara para cercar o terreno: R$%.2f", total);
    return 0;
}


Questão 51

// Escreva um programa que leia as coordenadas x e y de pontos no plano  
//cartesiano (R²) e calcule sua distância da origem (0, 0)
#include<stdio.h>
#include<math.h>
int main(){
float a,b,c,d;
 printf("digite o valor da coordenada x:\t");
 fflush(stdout);
 scanf("%f", &a);
 printf("digite o valor da coordenada y:\t");
 fflush(stdout);
 scanf("%f", &b);
 c=(a*a)+(b*b);
 d=sqrt(c);
 printf("A distancia entre os dois pontos no plano R² e:\t%f", d);
 printf("  unidades de medidas");
return 0;
}

Questão 44

#include <stdio.h>

/*Receba a altura do degrau de uma escada e a altura que o usuário
deseja alcançar subindo a escada.Calcule e mostre quantos degraus
o usuário deverá subir para atingir seu objetivo.*/

int main() {
   
    int degrau,altura,alt_cm;
    float qtde_degraus;
   
    printf("Informe a altura do degrau em centímetros\n");
    scanf("%d",&degrau);
    printf("Informe a altura que deseja alcançar em metros\n");
    scanf("%d",&altura);
    alt_cm=altura*100;
    qtde_degraus=alt_cm/degrau;
    printf("A qtde de degraus a subir para alcançar a altura desejada é: %.2f\n",qtde_degraus);
   
    return 0;
}

Questão 4

#include <stdio.h>
#include <stdlib.h>


int main() {
    int n=0;
    float quad=0;
    printf("Digite um numero: ");
    scanf("%d", &n);
    quad = n * n * n * n;
    printf("orig: %d Quad: %f", n, quad);
}

Questão 7

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/* Ler uma temperatura em graus Fahrenheit e apresentá-la convertida em graus Celsius. A
fórmula de conversão é: 𝐶 = 5,0 ∗ (𝐹 − 32,0)/9,0, sendo 𝐶 a temperatura em Celsius e 𝐹 a
temperatura em Fahrenheit.*/

int main() {
    float f, c;
    printf("Digite a temperatura em Graus Fahrenheit: ");
    scanf("%f", &f);
    c = 5.0*(f -32.0)/9.0;
    printf("A temperatura em Celsius eh: %.2f", c);
    return 0;
}


Questão 10

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/*  Ler uma velocidade em km/h (quilômetros por hora) e apresentá-la convertida em 𝑚/𝑠
(metros por segundo). A fórmula de conversão é: 𝑀 = 𝑘/3,6, sendo 𝐾 a velocidade em 𝑘𝑚/ℎ
e 𝑀 em m/s  */

int main() {
    float kmh, ms;
    printf("Digite a velocidade em Km/h: ");
    scanf("%f", &kmh);
    ms= kmh / 3.6;
    printf("\nA velocidade convertida em m/s : %.2f", ms);
    return 0;
}

Questão 21

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/*   Ler um valor de massa em quilogramas e apresentá-lo convertido em libras. A fórmula de
conversão é: 𝐿 = 𝐾/0,45 , sendo 𝐾 a massa em quilogramas e 𝐿 a massa em libras */

int main() {
    float kg, lb;
    printf("Digite massa em kg: ");
    scanf("%f", &kg);
    lb = kg /0.45;
    printf("\nO valor convertido em libras: %.2f",lb);
    return 0;
}

Questão 25

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/*   Ler um valor de área em acres e apresentá-lo convertido em metros quadrados 𝑚². A
fórmula de conversão é: 𝑀 = 𝐴 ∗ 4048,58 , sendo 𝑀 a área em metros quadrados e 𝐴 a área
em acres  */

int main() {
    float m2, ac;
    printf("Digite a area em acres: ");
    scanf("%f", &ac);
    m2 = ac * 4048.58;
    printf("\nA area em m2 eh: %.2f",m2);
    return 0;
}

Questão 26

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
/* Ler um valor de área em metros quadrados 𝑚² e apresentá-lo convertido em hectares. A
fórmula de conversão é: 𝐻 = 𝑀 ∗ 0,0001, sendo 𝑀 a área em metros quadrados e 𝐻 a área
em hectares */

int main() {
    float m2, hc;
    printf("Digite a area em m2: ");
    scanf("%f", &m2);
    hc = m2 * 0.0001;
    printf("\nA area em hectares eh: %.2f",hc);
    return 0;
}

Questão 30

#include <iostream>

int main() {



float real, dolar, calculo;

printf("Digite um valor: ");

scanf("%f", &real);

printf("Digite a cotacao do dolar: ");

scanf("%f", &dolar);



calculo = real * dolar;



printf("Valor em Dolar: $%.2f", calculo);



return 0;

}

Questão 33

#include <stdio.h>
#include <stdlib.h>

int main(void) {
    float l, a;
    printf("Digite o lado do quadrado:\n");
    scanf("%f",&l);
    a = l*l;
    printf("\n A area eh %f\n",a);
}

Questão 38

algoritmo "Novo salário"
// Função :   calcular novo salario de um funcionário
// Autor :   thazhandl
// Data : 01/10/2015
// Seção de Declarações
 var
sal, nsal: real
inicio
// Seção de Comandos 
escreva (" Informe o salário atual do funcionário: R$  ")
leia (sal)
nsal:= (sal*0.25)+ sal
escreval ("O atual salário do funcionário é: R$  ", nsal)
fimalgoritmo 

------------------------------------------------------------------------------------------------------------------
no pzim pascal

Program Pzim;
varsal,nsal: real;
Begin
write (' Informe o salário atual do funcionário: R$  '); 
read (sal);
nsal:= (sal*0.25)+ sal;
writeln ('O atual salário do funcionário é: R$  ', nsal:0:2); 
 End.
 
Questão 45.

#include <stdio.h>

int main()

{

   char caracter;

  

   scanf("%c", &caracter);

  

   int primeiro_maisculo = 'A';

   int primeiro_minusculo = 'a';

   int diferenca = primeiro_minusculo - primeiro_maisculo;

  

   printf("%c", caracter + diferenca);

   return 0;

}

Questão 46.

#include <stdio.h>
#include <stdlib.h>
#include <string.h>
/* Faça um programa para ler um número inteiro, positivo de três dígitos, e gerar outro
número formado pelos dígitos invertidos do número lido. Exemplo:
NúmeroLido = 123
NúmeroGerado = 321. */

int main() {
   int num, num1, num2, num3;
   printf("Digite um numero inteiro de 3 digitos positivo: ");
   scanf("%d", &num);
   if (num > 10) {
     num1 = num%10;
   num = num/10;
   num2 = num%10;
   num = num/10;
   num3=num%10;
   num=num/10;
   }
   printf("%d%d%d\n", num1, num2, num3);
   system("pause");
   return 0;
}

  Questão 2

#include <stdio.h>
#include <stdlib.h>
/*. Faça um programa que leia um número inteiro e o imprima, então leia um número real e
também o imprima. */

int main() {
    int a = 10;
    printf("Numero inteiro %d ",a);
    printf("\n");
    float b = 3.50;
    printf("Numero real %.2f ",b);
    printf("\n\n\n");
    system("pause");
    return 0;
}

Questão 33

#include <stdio.h>
#include <stdlib.h>

//  Leia o tamanho do lado de um quadrado e imprima como resultado a sua área :

int main() {
    int quadrado = 8 ;
    printf("O tamanho de um lado do quadrado e:%dcm" , quadrado);
    printf("\nA area do quadrado e: %dcm ",quadrado*quadrado);
    printf("\n\n");
    system("pause");
    return 0;
} 

