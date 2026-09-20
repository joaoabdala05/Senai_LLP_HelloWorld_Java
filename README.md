# 👋 Senai_LLP_HelloWorld_Java

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen)
![Contexto](https://img.shields.io/badge/contexto-acad%C3%AAmico%20SENAI%2FFATESG-blue)

## 📌 Sobre o projeto

Este repositório reúne três variações do clássico programa "Hello World", usadas como primeiro contato prático com a sintaxe, a compilação e a execução de programas em Java. Foi desenvolvido na disciplina de **Linguagem e Lógica de Programação (LLP)** do curso de **Análise e Desenvolvimento de Sistemas do SENAI/FATESG** — um dos meus exercícios mais iniciais na linguagem.

## 🎯 Objetivo

Compreender a estrutura mínima de um programa Java (classe + método `main`), o processo de compilação (`javac`) e execução (`java`), e as duas formas mais comuns de receber uma informação externa em um programa de console: **entrada interativa** (teclado, via `Scanner`) e **argumentos de linha de comando** (`args[]`).

## 🛠️ O que foi desenvolvido

Três programas, cada um explorando uma variação do "Hello World":

| Arquivo | O que faz |
|---|---|
| `HelloWorld.java` | Imprime a mensagem fixa `"Hello World!"` no console. |
| `HelloWorldInterativo.java` | Pergunta o nome do usuário via teclado e imprime `"Hello World "` seguido do nome digitado. |
| `HelloWorldParametro.java` | Imprime `"Hello World"` seguido de todos os argumentos recebidos pela linha de comando (`args[]`), se houver algum. |

## ⚙️ Como funciona

- `HelloWorld.java` não recebe nenhuma entrada — apenas executa `System.out.print` com uma string fixa.
- `HelloWorldInterativo.java` usa `Scanner` para ler uma linha de texto digitada pelo usuário e concatena essa entrada à saída.
- `HelloWorldParametro.java` percorre o array `args`, recebido pelo próprio método `main`, e imprime cada argumento passado na chamada do programa.

Para executar, por exemplo, o programa interativo:

```bash
javac HelloWorldInterativo.java
java HelloWorldInterativo
```

E o programa com parâmetros, passando argumentos na chamada:

```bash
javac HelloWorldParametro.java
java HelloWorldParametro SENAI FATESG
```

## 💻 Tecnologias utilizadas

- **Java (SE)** — linguagem usada nos três programas, sem dependências externas.
- **`java.util.Scanner`** — em `HelloWorldInterativo.java`, para capturar o nome digitado pelo usuário.
- **Parâmetro `String[] args`** — em `HelloWorldParametro.java`, para demonstrar o recebimento de argumentos externos na linha de comando.
- **Laço `for-each`** — usado para percorrer o array `args` e imprimir cada argumento recebido.

## ✅ Principais funcionalidades

- Saída fixa no console (exercício de sintaxe básica).
- Saída personalizada a partir de entrada digitada pelo usuário.
- Saída dinâmica a partir de argumentos passados na execução do programa.

## 📁 Estrutura do projeto

```
Senai_LLP_HelloWorld_Java/
├── HelloWorld.java              # Hello World fixo
├── HelloWorldInterativo.java    # Hello World com nome digitado pelo usuário
└── HelloWorldParametro.java     # Hello World com argumentos de linha de comando
```

## 📚 O que foi aprendido

- A estrutura mínima obrigatória de um programa Java (`public class` + `public static void main`).
- O ciclo básico de compilação e execução de um programa Java a partir do terminal.
- A diferença entre receber dados por entrada interativa (`Scanner`) e por argumentos de linha de comando (`args[]`).

## 🎓 Contexto acadêmico

Este repositório é, literalmente, um dos **meus primeiros programas publicados no GitHub** durante o início da minha formação em **Análise e Desenvolvimento de Sistemas no SENAI/FATESG**. Ele marca o ponto de partida da minha evolução como estudante da área: o primeiro contato com a sintaxe de uma linguagem de programação orientada a objetos e com o fluxo de versionamento de código no Git/GitHub.

## ⚠️ Observações

São programas propositalmente simples — sem tratamento de exceções, validação de entrada ou qualquer lógica de negócio — já que o objetivo do exercício era exclusivamente compreender a sintaxe básica e o fluxo de compilação/execução do Java, não resolver um problema complexo.

## 👤 Autor

**João Pedro Abdala** — estudante de Análise e Desenvolvimento de Sistemas (SENAI/FATESG)
[github.com/joaoabdala05](https://github.com/joaoabdala05)
