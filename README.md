# Desafio Controle de Fluxo

Este repositório contém a solução para o desafio de Controle de Fluxo proposto. O objetivo é criar um programa em Java que receba dois números inteiros como entrada e realize a contagem incremental entre eles, imprimindo os valores no console. Caso o primeiro número seja maior que o segundo, uma exceção personalizada será lançada.

## 📌 Tecnologias Utilizadas
- Java
- Scanner para entrada de dados
- Estruturas de controle de fluxo (`for`, `if`)
- Tratamento de exceções personalizadas

## 🚀 Como Executar o Projeto
1. Clone este repositório:
   ```bash
   https://github.com/DavidBrito06/desafio-controle-fluxo.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd desafio-controle-fluxo
   ```
3. Compile o código Java:
   ```bash
   javac Contador.java
   ```
4. Execute o programa:
   ```bash
   java Contador
   ```

## 📜 Regras de Funcionamento
- O programa solicita dois números inteiros ao usuário.
- Caso o primeiro número seja **maior ou igual** ao segundo, será lançada a exceção `ParametrosInvalidosException`.
- Se os valores forem válidos, o programa imprimirá os números incrementados de 1 até a diferença entre os dois.

### 🔹 Exemplo de Entrada e Saída
**Entrada:**
```
Digite o primeiro número inteiro:
12
Digite o segundo número inteiro:
30
```
**Saída:**
```
Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18
```

