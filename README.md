# Alfabeto-LCD
Três programas em assembly para um trabalho de faculdade (UNESP, 2014).

## Programa 1
  Neste programa foram-se utilizadas duas sub-rotinas (IniciaLCD e WriteLCD)
com os objetivos de se iniciar o LCD e de se passar os comandos para o LCD,
respectivamente e uma interrupção em INT0 (escreve) com o objetivo de se escrever o
alfabeto na primeira posição do LCD.

![Primeiro Programa](https://github.com/Montevani/Alfabeto-LCD/blob/main/Flow1.jpg)

## Programa 2
  Neste programa se foram usadas 4 sub-rotinas: IniciaLCD que possui o
objetivo de iniciar o LCD, WriteCMD com o objetivo de enviar comandos ao LCD,
Atraso para servir de intervalo entre o aparecimento de cada caractere e Escreve que
faz a função de escrever o alfabeto no display.
Foram usados registradores para se contar a posição do cursos e se assegurar
que não apareceria outros caracteres que não fossem as letras do alfabeto no display,
ou seja, parando no Z.

![Segundo Programa](https://github.com/Montevani/Alfabeto-LCD/blob/main/Flow2.jpg)

## Programa 3
Assim como o programa anterior, este também possui quatro sub-rotinas
genéricas com as mesmas funções, IniciaLCD, WriteCMD, Atraso e Escreve. Porém,
no lugar de escrever o alfabeto nas duas primeiras linhas do display este programa foi
feito para fazer uma contagem regressiva de 6 até 0 intercalada de asteriscos,
formando o desenho “*6*5*4*3*2*1*0*” na primeira linha do display.
Para alcançar este objetivo se foi utilizado comandos de reposicionamento do
cursor, assim como a utilização do datasheet para se encontrar os caracteres
necessários.

![Terceiro Programa](https://github.com/Montevani/Alfabeto-LCD/blob/main/Flow3.jpg)
