# Cartão de Crédito - Simulação de Compras

Este projeto simula o controle de um cartão de crédito com limite definido, onde o usuário pode realizar compras e acompanhar o saldo disponível no cartão. O sistema permite ao usuário realizar múltiplas compras até que o saldo do cartão seja insuficiente.

## Funcionalidades

- **Definição de Limite**: O usuário define o limite do cartão ao inicializar o sistema.
- **Compra no Cartão**: O usuário pode realizar compras, informando a descrição e o valor da compra.
- **Controle de Saldo**: O saldo do cartão é descontado a cada compra realizada, e o sistema impede a realização de compras caso o saldo seja insuficiente.
- **Relatório de Compras**: O sistema exibe todas as compras realizadas, ordenadas pelo valor da compra.
- **Encerramento do Sistema**: O usuário pode escolher continuar realizando compras ou encerrar o programa.

## Estrutura do Projeto

O projeto é composto por três classes principais:

- **Principal**: Classe com o método `main`, que gerencia a interação com o usuário, lê os dados de entrada, realiza as compras e exibe o saldo final.
- **CartaoDeCredito**: Classe que representa o cartão de crédito, gerencia o limite, o saldo e as compras realizadas.
- **Compra**: Classe que representa uma compra realizada, com descrição e valor, implementando a interface `Comparable` para possibilitar a ordenação das compras pelo valor.

## Como Executar

1. Clone este repositório.
2. Compile os arquivos Java:
   ```bash
   javac Principal.java CartaoDeCredito.java Compra.java
3. Execute o programa:
  java Principal
4. O programa solicitará que você insira o limite do cartão, as descrições e os valores das compras. O programa continuará até que o saldo do cartão seja insuficiente ou o usuário escolha sair.
