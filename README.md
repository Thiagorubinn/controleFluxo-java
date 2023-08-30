# controleFluxo-java
Documentação do Código - Contador
Este é um programa Java simples que permite ao usuário inserir dois parâmetros e, em seguida, gera uma contagem de números a partir do primeiro parâmetro até o segundo parâmetro. O programa também trata exceções de entrada de parâmetros inválidos.

Utilização
Classe Principal (contador.main())

A função principal do programa está contida na classe contador. Ela solicita ao usuário que insira dois parâmetros inteiros. Esses parâmetros são passados para o método contar() para realizar a contagem.

Método de Contagem (contar(int parametroUm, int parametroDois))

Este método gera uma contagem de números a partir do primeiro parâmetro até o segundo parâmetro. Se o segundo parâmetro for menor que o primeiro, ele lança uma exceção ParametrosInvalidosException. Caso contrário, a contagem é executada, exibindo os números em ordem crescente.

Classe de Exceção (ParametrosInvalidosException)

Essa classe define uma exceção personalizada chamada ParametrosInvalidosException, que é lançada quando o segundo parâmetro é menor que o primeiro. Ela é capturada no bloco catch da função principal e exibe uma mensagem de erro.

Utilizando o Programa
O programa solicitará ao usuário para inserir o primeiro e o segundo parâmetros.
Se o segundo parâmetro for menor que o primeiro, o programa capturará a exceção e exibirá uma mensagem de erro.
Caso contrário, a contagem será gerada e os números serão exibidos em ordem crescente.
Considerações Finais
Este programa Java demonstra o uso de entrada de dados, tratamento de exceções e geração de uma contagem de números. Ele pode ser usado como exemplo didático para entender conceitos básicos de entrada/saída, manipulação de exceções e estruturas de controle de fluxo. É importante notar que o programa poderia ser estendido para lidar com diferentes tipos de contagens ou até mesmo com requisitos mais complexos.
