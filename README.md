# Turing-Machine-Calculadora-de-bits

Este trabalho consiste no desenvolvimento de uma Máquina de Turing, doravante MT, para resolver
operações de soma, subtração e multiplicação de inteiros binários. A MT projetada deverá ser
implementada no simulador disponível em http://morphett.info/turing/turing.html.

2. Entrada:
No início da execução, a fita contém a operação a ser realizada. O formato da entrada é
<num><op><num>=
onde <num> é um número binário positivo e <op> é “+”, “-” ou “*”. O cabeçote da fita inicia no
primeiro caractere da entrada. Exemplos:
  01001+11101= 
  1001-11101=
  01001*1111=

3. Saída:
No final da execução, a fita deverá mostrar a operação especificada na entrada seguida do resultado
da operação (depois do “=”) em complemento de 2.
Exemplos:
  01001+11101=0100110
  1001-11101=101100
  1001*011=011011
