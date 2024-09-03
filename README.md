# Resolvendo Problemas Numéricos com Go

# Programa para Números Divisíveis por 3:

Objetivo: Exibir todos os números entre 1 e 100 que são divisíveis por 3.
Funcionamento: Utiliza um loop for para iterar através dos números de 1 a 100. 
Para cada número, verifica se ele é divisível por 3 usando o operador %. 
Se a condição (i % 3 == 0) for verdadeira, o número é impresso.

# Programa para "Pin", "Pan" e "Pinpan":

Objetivo: Imprimir "pin" para múltiplos de 3, "pan" para múltiplos de 5 e "pinpan" para múltiplos de 3 e 5. 
Números que não são múltiplos de 3 ou 5 são impressos diretamente.
Funcionamento: Um loop for itera de 1 a 100. Para cada número:

Verifica se é múltiplo de 3 e 5 (i % 3 == 0 && i % 5 == 0) e imprime "pinpan".
Se é múltiplo apenas de 3 (i % 3 == 0), imprime "pin".
Se é múltiplo apenas de 5 (i % 5 == 0), imprime "pan".
Caso contrário, imprime o próprio número.

Esses exemplos demonstram como usar loops e o operador de módulo para realizar operações condicionais e gerar saídas baseadas em múltiplos. 
São ótimos para praticar a lógica de programação e a sintaxe da linguagem Go.
