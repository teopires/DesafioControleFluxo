## Controle de Fluxo - Desafio DIO


Este projeto em Java solicita dois números inteiros via terminal e imprime uma sequência de números incrementados. Se o primeiro número for maior que o segundo, uma exceção customizada é lançada.

## Funcionalidades

- Solicita dois números inteiros via terminal.
- Imprime uma sequência de números incrementados com base na diferença entre os dois números.
- Lança uma exceção customizada se o primeiro número for maior que o segundo.

## Como Usar

1. Clone este repositório para sua máquina local.
2. Navegue até o diretório do projeto.
3. Compile o programa usando o comando `javac Contador.java`.
4. Execute o programa usando o comando `java Contador`.
5. Siga as instruções no terminal para inserir os parâmetros.

## Exemplo de Uso

```sh
Digite o primeiro parâmetro:
12
Digite o segundo parâmetro:
30

Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18

Se o primeiro parâmetro for maior que o segundo:

Digite o primeiro parâmetro:
30
Digite o segundo parâmetro:
12

O segundo parâmetro deve ser maior que o primeiro

Estrutura do Projeto
Contador.java: Contém a lógica principal do programa.
ParametrosInvalidosException.java: Define a exceção customizada.
Requisitos
Java JDK 8 ou superior
Autor
Teo Pires Marques
