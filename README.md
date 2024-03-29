# Sistema de Loteria em Java - LotoFácil 🎰

## Descrição:
O sistema chamado LotoFácil, tem como objetivo gerar jogos aleatórios, permitir que os jogadores façam suas apostas, verificar os resultados e calcular prêmios de acordo com as regras da loteria. Este sistema funciona por meio do terminal, lendo e escrevendo dados. 

## Requisitos do Projeto:
Este repositório contém as especificações detalhadas para a implementação de um menu de loteria, utilizando as estruturas `switch case` e `do while`. O menu permite ao usuário fazer diferentes tipos de apostas enquanto não optar por sair do sistema digitando o número zero.

**Menu LOTOFÁCIL:**
1) Apostar de 0 a 100
2) Apostar de A à Z
3) Apostar em par ou ímpar
0) Sair

**Regras para a Aposta de 0 a 100:**
- Leia um número inteiro via teclado, de 0 a 100. Caso o número seja maior que 100 ou menor que 0, imprima a mensagem: “Aposta inválida.”.
- Utilize a biblioteca `Random` para sortear aleatoriamente um número de 0 a 100.
- Compare o número escolhido pelo usuário apostador com o número sorteado pelo sistema.
- Se o usuário acertar a aposta, imprima a mensagem “Você ganhou R$ 1.000,00 reais.”. Caso contrário, imprima: “Que pena! O número sorteado foi: X.”.

**Regras para a Aposta de A à Z:**
- Leia um caractere via teclado, de A à Z, podendo ser lido como maiúsculo ou minúsculo. Caso não seja uma letra, imprima: “Aposta inválida.”.
- Converta a entrada do usuário apostador para maiúsculo, utilizando o método `Character.toUpperCase()`.
- Compare a letra lida via teclado, convertida para maiúsculo, com a letra premiada.
- Se o usuário acertar a aposta, imprima “Você ganhou R$ 500,00 reais.”. Caso contrário, imprima: “Que pena! A letra sorteada foi: X.”.

**Regras para a Aposta de Número Par ou Ímpar:**
- Leia um número inteiro via teclado.
- O prêmio será dado caso o usuário digite um número par. O sistema não irá premiar jogadores que digitarem um número ímpar.
- Se o número digitado for par, imprima “Você ganhou R$ 100,00 reais.”. Caso o usuário digite um número ímpar, imprima: “Que pena! O número digitado é ímpar e a premiação foi para números pares.”.

### Como executar e especificações do Código
- Para rodar o programa, copie o código-fonte do arquivo Main.java para sua IDE, compile e execute-o;
- **JDK:** O projeto foi desenvolvido e testado utilizando o JDK 21.0.2;
**Bibliotecas Utilizadas:**
- `java.util.Scanner`: Utilizada para receber entrada do usuário a partir do console.
- `java.io.*`: Utilizada para operações de entrada e saída de dados, como leitura de entrada do teclado e exibição de mensagens.
- `java.util.Random`: Utilizada para gerar números aleatórios.
- `java.io.IOException`: Utilizada para tratar exceções relacionadas a operações de entrada e saída de dados.
- `java.util.InputMismatchException`: Utilizada para capturar exceções relacionadas a entradas de dados incorretas.
- `java.lang.Object`: Importada implicitamente, é a superclasse de todas as classes no Java.

## Conclusão
Esse programa foi fundamental para o esclarecimento de aplicações simples em Java, como entrada de dados, controle de fluxo e manipulação de exceções.

