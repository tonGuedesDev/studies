# Separando as funções das rotas

conforme o tempo passa e o projeto cresce, será necessário separar as funções das rotas.

1 - Criar um arquivo separado na mesma pasta das rotas </br>
2 - exporta as funções.
    existem 2 maneiras de fazer essa exportação:

    ```
    module.export = "aqui vai oque você quer exporta"
    ```

    ou 

    ```
    export.nomeAsuaEscolha = "aqui vai oque você quer exporta"
    ```

module.exports retorna um módulo com apenas uma função. </br>
exports retorna um objeto com a possibilidade de ter diversas funções nele.

</br>
3 - fazer a chamada da função que você exportou usando o require()