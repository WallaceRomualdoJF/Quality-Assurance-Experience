
# Blindando Seu Código com TDD e Testes Unitários Usando .NET Core

Este repositório contém o projeto desenvolvido para o desafio **"Blindando Seu Código com TDD e Testes Unitários Usando .NET Core"**, disponível na plataforma **Digital Innovation One (DIO)**. O objetivo do projeto é aplicar a metodologia de **Test-Driven Development (TDD)** para o desenvolvimento de uma aplicação de calculadora.

## Objetivo do Projeto

O projeto tem como principal objetivo demonstrar a aplicação prática do **Test-Driven Development (TDD)** utilizando **.NET Core**. Durante o desenvolvimento da aplicação, aplicamos os princípios de TDD, escrevendo os testes antes da implementação das funcionalidades. O projeto também visa fornecer uma base para a criação de código para a calculadora, com a utilização de **testes unitários** para validação do comportamento das funcionalidades de forma contínua e segura.

Neste projeto, foi desenvolvida uma aplicação **console** que simula uma **calculadora**, implementando as operações básicas de matemática e mantendo um **histórico das últimas três operações**. As funcionalidades implementadas são:

- **Somar dois números**.
- **Subtrair dois números**.
- **Multiplicar dois números**.
- **Dividir dois números**.
- **Histórico das últimas três operações realizadas**.

Os testes para estas operações foram desenvolvidos utilizando o framework **XUnit**, seguindo o ciclo de TDD.


## Funcionalidades Implementadas

A aplicação console implementa uma **calculadora simples** com as seguintes funcionalidades:

- **Somar dois números**: Realiza a soma de dois valores numéricos.
- **Subtrair dois números**: Realiza a subtração entre dois valores numéricos.
- **Multiplicar dois números**: Realiza a multiplicação entre dois valores numéricos.
- **Dividir dois números**: Realiza a divisão entre dois valores numéricos, com tratamento de erro para divisão por zero.
- **Histórico das últimas três operações**: Armazena e exibe as três últimas operações realizadas.

### Benefícios do TDD

- **Código Mais Robusto**: TDD ajuda a criar código mais seguro e confiável, pois valida continuamente as funcionalidades.
- **Facilidade de Refatoração**: Com os testes já escritos, é possível refatorar o código sem o medo de introduzir bugs.
- **Documentação Viva**: Os testes atuam como uma documentação clara do comportamento esperado do sistema.
- **Ciclo Ágil de Desenvolvimento**: TDD permite um ciclo ágil e iterativo de desenvolvimento, com feedback constante e rápido.

## Licença

Este repositório está licenciado sob a [MIT License](LICENSE).