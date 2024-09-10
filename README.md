# Projeto de Implementação de Stack (Pilha) em Java

Este projeto contém a implementação de uma classe genérica `Stack` em Java, utilizando um `ArrayList` internamente. A classe possui métodos para inserir, remover e verificar o estado da pilha, assim como métodos auxiliares como `isEmpty` e `size`.

Além da implementação da pilha, o projeto inclui testes unitários, escritos com o framework JUnit, para garantir o correto funcionamento da classe.

## Estrutura do Projeto

- `Stack.java`: Implementação da classe `Stack`, uma pilha genérica que armazena elementos de qualquer tipo.
- `StackTest.java`: Arquivo contendo testes unitários para verificar o comportamento da classe `Stack`.

## Funcionalidades

### Métodos da classe `Stack`
- `push(T elem)`: Insere um elemento no topo da pilha.
- `pop()`: Remove e retorna o elemento do topo da pilha. Lança uma exceção `EmptyStackException` se a pilha estiver vazia.
- `isEmpty()`: Retorna `true` se a pilha estiver vazia, caso contrário, `false`.
- `size()`: Retorna o número de elementos na pilha.

### Testes Implementados

- `testEmptyStack()`: Verifica se uma nova pilha está vazia.
- `testNotEmptyStack()`: Verifica se a pilha não está vazia após inserir um elemento.
- `testSizeStack()`: Testa o método `size()` após adicionar múltiplos elementos.
- `testPushPopStack()`: Testa a inserção e remoção de elementos da pilha.
- `testEmptyStackException()`: Verifica se a exceção `EmptyStackException` é lançada ao tentar remover um elemento de uma pilha vazia.

## Pré-requisitos

- [Java JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) 11 ou superior
- [JUnit](https://junit.org/junit5/) para rodar os testes unitários


