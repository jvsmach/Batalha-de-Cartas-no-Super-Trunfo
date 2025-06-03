Super Trunfo das Cidades – Nível Intermediário
Este projeto é um programa em linguagem C que simula o cadastro de cartas de cidades brasileiras para um jogo estilo Super Trunfo. 
Ele permite ao usuário inserir dados de duas cidades e calcula automaticamente métricas importantes, como densidade populacional e PIB per capita.

Funcionalidades

Cadastro de duas cartas contendo:
Estado (letra de A a H)
Código da carta (ex: A01)
Nome da cidade
População
Área da cidade (em km²)
PIB (em bilhões de reais)
Número de pontos turísticos

Cálculos automáticos:
Densidade Populacional = População / Área
PIB per Capita = (PIB × 1.000.000.000) / População
Exibição formatada dos dados cadastrados, incluindo as métricas calculadas com duas casas decimais

Conceitos aplicados
Leitura e formatação de dados com scanf e printf
Manipulação de strings e números em C
Cálculo de métricas populacionais e econômicas

Organização e legibilidade de código para fins educacionais.

Exemplo de Saída
yaml
Copiar
Editar
=== Carta 1 ===
Estado: A
Código: A01
Nome da Cidade: São Paulo
População: 12325000
Área: 1521.11 km²
PIB: 699.28 bilhões de reais
Número de Pontos Turísticos: 50
Densidade Populacional: 8102.47 hab/km²
PIB per Capita: 56724.32 reais

=== Carta 2 ===
Estado: B
Código: B02
Nome da Cidade: Rio de Janeiro
População: 6748000
Área: 1200.25 km²
PIB: 300.50 bilhões de reais
Número de Pontos Turísticos: 30
Densidade Populacional: 5622.24 hab/km²
PIB per Capita: 44532.91 reais
🚀 Como executar

Compile o programa com um compilador C, por exemplo:

bash
gcc super_trunfo_cidades.c -o super_trunfo

Execute o programa:

bash
./super_trunfo

Siga as instruções no terminal para cadastrar os dados das cidades.

Requisitos
Linguagem: C (ANSI C)
Nenhuma biblioteca externa necessária
Recomendado usar compiladores como gcc ou clang

Aprendizado

Entrada e saída de dados em C
Tipos primitivos (char, int, float)
Cálculo de métricas com variáveis
Organização básica de programas em C
