DesafioControleFluxo
Este projeto é um desafio de programação em Java que demonstra o controle de fluxo e o tratamento de exceções. Ele recebe dois parâmetros via terminal e realiza uma contagem de números inteiros com base nesses parâmetros.

Requisitos
Java Development Kit (JDK) instalado no seu sistema.
Um ambiente de desenvolvimento Java, como Eclipse, IntelliJ IDEA ou uma IDE de sua escolha.
Como usar
Clone ou faça o download deste repositório.

Abra o terminal e navegue até o diretório raiz do projeto.

Compile o código usando o seguinte comando:
javac Contador.java
Execute o programa com os dois parâmetros (números inteiros) da seguinte maneira:
java Contador
Você será solicitado a inserir o primeiro parâmetro e, em seguida, o segundo parâmetro.

O programa realizará a contagem dos números no intervalo especificado e imprimirá cada número no console. Se o primeiro parâmetro for maior que o segundo, o programa lançará uma exceção personalizada.
Exemplo de uso
Digite o primeiro parâmetro:
1
Digite o segundo parâmetro:
10

Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
Imprimindo o número 5
Imprimindo o número 6
Imprimindo o número 7
Imprimindo o número 8
Imprimindo o número 9
Imprimindo o número 10

Digite o primeiro parâmetro:
15
Digite o segundo parâmetro:
5

O segundo parâmetro deve ser maior que o primeiro
Estrutura do Projeto
Contador.java: Contém a classe principal que realiza a contagem com base nos parâmetros fornecidos e lida com exceções.
ParametrosInvalidosException.java: Contém a classe da exceção personalizada ParametrosInvalidosException.
Contribuição
Fique à vontade para contribuir para este projeto, sugerir melhorias ou relatar problemas. Abra um problema (issue) ou envie uma solicitação de pull (pull request).
