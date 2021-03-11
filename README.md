# Aprendendo Java-Rest com o Livro APIs REST: Seus serviços prontos para o mundo real
* Tecnologias
    - Java 11
    - Spring boot
    - Maven

* O que são recursos?
    - Quando é definido uma URL e um tipo de retorno (EX: json)

* HTTP status
    - 1xx
        * Informações, como a requisição foi recebida e algo está processando.
    - 2xx
        * Sucesso
        * Finalizou o processamento
        * Geralmente 200 é o ok de sucesso
    - 3xx
        * Redirecionamento
    - 4xx
        * Falha
        * Algo errado que o cliente fez
        * Erros de validação
    - 5xx
        * Erro do servidor
        * Condição não tratada

* POSTMAN
    - Headers
        * Accepet: */* -> Aceita qualquer coisa, json, html etc, wildcard para mime type
        * mime types: application -> binário -> <tipo>/<subtipo>
* Idempotência
    - Propriedade http que define que o verbo sempre tera a mesma saída, nao importa quantas vezes for chamado
