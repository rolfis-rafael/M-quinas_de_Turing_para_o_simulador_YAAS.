# Simulador-YAAS-M-quinas-de-Turing-de-Subtra-o-e-Resto
Duas Máquinas de Turing para o simulador YAAS, feitas a partir dos exemplos Monus e Divide.

Arquivos
Arquivo	Função	Entrada	Saída
subtracao.ytm	Subtração entre inteiros	0^m 1 0^n	0^(m−n) ou -0^(n−m)
resto.ytm	Resto da divisão inteira	0^m 1 0^n 1	0^(m mod n)

Os números são representados em unário, e o separador é o símbolo 1.

Exemplos

Subtração (subtracao.ytm)

Entrada	Operação	Saída
03102	3 − 2	01
02102	2 − 2	00
02103	2 − 3	-01

Resto (resto.ytm)

Entrada	Operação	Saída
051031	5 % 3	02
051051	5 % 5	00
031051	3 % 5	03
Como usar
Abra o YAAS.
Carregue subtracao.ytm ou resto.ytm pelo menu File → Open.
Digite a entrada no campo de teste e execute em Accept by Halt.
Verificação

As duas máquinas foram testadas com 325 combinações de valores, de 0 a 12, no motor de simulação do próprio YAAS. Todos os resultados conferiram, inclusive depois de salvar e reabrir os arquivos.

Licença

Este projeto usa o simulador YAAS, que tem licença GPL-3.0. Os exemplos Monus e Divide são do autor do YAAS, Prof. Dr. David Buzatto.
