Super Trunfo das Cidades
Nível Avançado

Este programa em C simula um jogo de cartas do tipo "Super Trunfo", onde cada carta representa uma cidade com atributos numéricos. No nível avançado, foram adicionadas novas funcionalidades como o cálculo do "Super Poder" da cidade e a comparação entre cartas.

Funcionalidades

Leitura dos dados de duas cartas com os seguintes atributos:
Estado (caractere)
Código (string)
Nome da cidade (string)
População (unsigned long int)
Área (float)
PIB em bilhões de reais (float)
Número de pontos turísticos (int)

Cálculo automático de:
Densidade populacional (hab/km²)
PIB per capita (R$ por habitante)
Super Poder da carta (soma ponderada dos atributos)

Comparação entre as cartas com base nos atributos:
População, área, PIB, pontos turísticos, PIB per capita e Super Poder: vence quem tiver o maior valor

Densidade populacional: vence quem tiver o menor valor

Exibição dos resultados das comparações entre as duas cartas.

--------

Como compilar
Use um compilador C, como gcc, para compilar o programa:

nginx
gcc super_trunfo_avancado.c -o super_trunfo

Como executar
Após a compilação, execute o programa:

bash

./super_trunfo

Siga as instruções no terminal para inserir os dados de cada carta. O programa exibirá os cálculos e comparações automaticamente.

Observações
Os cálculos consideram conversão do PIB para reais (multiplicado por 1.000.000.000)
A densidade populacional é usada de forma inversa no cálculo do Super Poder (quanto menor, melhor)
O programa mantém todas as funcionalidades dos níveis básico e intermediário.

