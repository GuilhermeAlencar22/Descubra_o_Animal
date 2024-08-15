# README para o Projeto de Jogo em C: Descubra o Animal

## Descrição
Este programa em C é um jogo interativo de adivinhação chamado "Descubra o Animal". Ele permite que dois jogadores se revezem para adivinhar animais com base em dicas fornecidas. Os animais estão categorizados em diferentes ecossistemas, como deserto, oceano, floresta, neve e montanha, e os jogadores podem escolher o ecossistema e o nível de dificuldade antes de começar a adivinhar.

## Funcionalidades

- **Criação e Gerenciamento de Listas**: Utiliza uma lista encadeada para armazenar informações sobre cada animal, incluindo nome, dicas e dificuldade.
- **Seleção de Animais e Dicas**: Permite aos jogadores escolher animais de um ecossistema específico e receber dicas para adivinhar o nome do animal.
- **Jogo Interativo**: Suporta dois jogadores e mantém a pontuação, fornecendo uma experiência competitiva.
- **Manipulação Dinâmica de Dados**: Utiliza alocação dinâmica de memória para gerenciar os dados dos animais durante o jogo.

## Estrutura do Código

O código é dividido em várias funções para facilitar a gestão e a manutenção:

- **criarAnimalNode**: Cria um novo nó na lista para um animal, inicializando com o nome, dicas e dificuldade.
- **adicionarAnimalOrdenado**: Adiciona um animal na lista em ordem alfabética baseado no nome.
- **liberarLista**: Libera toda a memória alocada para a lista quando o jogo termina.
- **selecionarAnimalAleatorio**: Escolhe um animal aleatório de um ecossistema com base na dificuldade selecionada.
- **selecionarListaEcossistema**: Retorna a lista de animais para o ecossistema escolhido.
- **main**: Contém a lógica principal do jogo, tratamento de entradas e saídas, e fluxo do jogo.

## Compilação e Execução

Para compilar e executar o programa, siga estas instruções:
1. Abra o terminal ou prompt de comando.
2. Navegue até o diretório onde o arquivo de código fonte está salvo.
3. Compile o programa usando o compilador GCC:
   ```
   gcc -o descubra_o_animal jogo.c
   ```
4. Execute o programa:
   ```
   ./descubra_o_animal
   ```

## Dependências

- Bibliotecas padrão do C: `<stdio.h>`, `<stdlib.h>`, `<string.h>`, `<strings.h>`, `<time.h>`, e `<unistd.h>`.
- Compilador GCC para compilação do código.

## Conclusão

Este jogo oferece uma maneira divertida e educativa de aprender sobre animais de diferentes ecossistemas, testando o conhecimento dos jogadores de maneira interativa. É ideal para jogar em ambiente educacional ou como uma atividade recreativa entre amigos e familiares.

---

Para mais informações sobre modificações e personalizações, sinta-se à vontade para examinar e modificar o código conforme necessário. Divirta-se jogando e aprendendo com o "Descubra o Animal"!
