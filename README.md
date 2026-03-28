# una-ihcux-lista04-

# Projeto de Avaliação de Interface

## Descrição

Este projeto tem como objetivo analisar uma interface digital com base nas heurísticas de Nielsen, identificando problemas de usabilidade e propondo melhorias.

## Heurística de Nielsen - Visibilidade do Status do Sistema

A heurística de visibilidade do status do sistema estabelece que o sistema deve sempre manter o usuário informado sobre o que está acontecendo, por meio de feedbacks claros e em tempo adequado.

Isso inclui mensagens de carregamento, confirmações de ações e avisos de erro, garantindo que o usuário nunca fique sem entender o que está acontecendo no sistema.

## Tratamento de Erros com Try-Catch

O try-catch é uma estrutura utilizada em linguagens de programação para tratar erros que podem ocorrer durante a execução de um programa.

Ele funciona da seguinte forma:

* **try**: onde fica o código que pode gerar erro
* **catch**: onde o erro é capturado e tratado

### Exemplo:

```java id="k2j8d1"
try {
    int resultado = 10 / 0;
} catch (Exception e) {
    System.out.println("Ocorreu um erro: " + e.getMessage());
}
```

Nesse caso, ocorre um erro de divisão por zero, mas o programa não para de funcionar, pois o erro é tratado.

### Relação com a prevenção de erros

O try-catch não evita que erros aconteçam, mas ajuda a evitar que o sistema falhe completamente. Ele permite que o programa continue funcionando mesmo após um erro, melhorando a estabilidade e a experiência do usuário.

