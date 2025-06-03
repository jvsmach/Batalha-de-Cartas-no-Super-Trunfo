# Super Trunfo - Países

Este programa em C implementa o cadastro e a comparação de cartas no jogo "Super Trunfo" com tema de países e cidades, conforme o desafio proposto.

No **Nível Mestre**, o programa:

- Permite cadastrar dados de duas cartas, cada uma representando uma cidade.
- Cada carta possui os atributos:
  - População (unsigned long int)
  - Área (float)
  - PIB (float)
  - Número de pontos turísticos (int)
- Calcula automaticamente os atributos adicionais:
  - Densidade Populacional (População / Área)
  - PIB per Capita (PIB / População)
  - Super Poder: soma dos atributos (população, área, PIB, pontos turísticos, PIB per capita, e 1 / densidade populacional)
- Compara atributo a atributo as duas cartas, mostrando qual venceu para cada um:
  - Para Densidade Populacional, vence a carta com menor valor
  - Para os demais atributos e o Super Poder, vence a carta com maior valor.

O programa não utiliza estruturas de repetição ou condicionais (`for`, `while`, `if`, `else`), atendendo às especificações do desafio.

## Observações
- O programa considera que todos os dados informados são válidos e não realiza validação de entrada
- A fórmula do "Super Poder" inclui o inverso da densidade populacional para equilibrar seu impacto
- A comparação das cartas é feita diretamente usando expressões lógicas, sem comandos condicionais explícitos.

---

## Como usar

- Compile o programa com um compilador C, por exemplo:

   bash  
   gcc -o supertrunfo mestre_supertrunfo.c
  
 - Execute o programa: 
   ./supertrunfo
   
 - Insira os dados das duas cartas quando solicitado:
  - População (número inteiro grande)
  - Área (número decimal)
  - PIB (número decimal)
  - Número de pontos turísticos (inteiro)
- O programa exibirá os resultados da comparação dos atributos e o "Super Poder" de cada carta, indicando qual carta venceu em cada atributo (1 para Carta 1 e 0 para Carta 2).




