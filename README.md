# SistemaEstacionamentoDotnet
Sistema de Estacionamento bem simples com menu iterativo, construído em dotnet durante as aulas ministradas pela Digital Innovation One. 

## Classe Estacionamento
Contém os atributos preço inicial, preço por hora e lista de veículos. 
Foi implementado os métodos Cadastrar, Remover, Listar e Atualizar placa de um veículo.
Foi implementado o metódo "VerificaPlacaValida", que utilizando de uma expressão regular REGEX, é válidado se a placa segue o formato (AAA-1234).

## Classe Main
Foi implementado um menu iterativo, além de inserido as váriavéis de preco_inial e preco_por_hora que terão seus valores lidos pelo usuário e então após será enviado por parâmetro para o nosso objeto Emprestimo aqui instanciado.

