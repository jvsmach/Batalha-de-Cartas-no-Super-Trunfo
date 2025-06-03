# Super Trunfo das Cidades

Este programa em C simula um jogo de cartas do tipo "Super Trunfo", onde cada carta representa uma cidade com atributos numéricos. No nível avançado, foram adicionadas funcionalidades como o cálculo do **Super Poder** da cidade e a **comparação entre cartas**.

---

## Funcionalidades

- Leitura dos dados de duas cartas com os seguintes atributos:
  - Estado (caractere)
  - Código (string)
  - Nome da cidade (string)
  - População (`unsigned long int`)
  - Área (`float`)
  - PIB em bilhões de reais (`float`)
  - Número de pontos turísticos (`int`)

- Cálculos automáticos:
  - Densidade populacional (hab/km²)
  - PIB per capita (R$ por habitante)
  - Super Poder da carta (soma ponderada dos atributos)

- Comparações:
  - **População, Área, PIB, Pontos Turísticos, PIB per Capita, Super Poder** → vence quem tiver o maior valor
  - **Densidade Populacional** → vence quem tiver o menor valor

- Exibição dos resultados das comparações entre as duas cartas.

## Observações
- Observações
- Os cálculos consideram a conversão do PIB para reais (multiplicando por 1.000.000.000)
- A densidade populacional é usada de forma inversa no cálculo do Super Poder (quanto menor, melhor)
- O programa mantém todas as funcionalidades dos níveis básico e intermediário

---

## Como compilar

Use um compilador C, como `gcc`, para compilar o programa:

```bash
gcc super_trunfo_avancado.c -o super_trunfo

```bash
./super_trunfo```


