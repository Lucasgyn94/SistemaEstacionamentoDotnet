# SistemaEstacionamentoDotnet
Sistema de Estacionamento bem simples com menu iterativo, construído em dotnet durante as aulas ministradas pela Digital Innovation One. 

## Classe Estacionamento
Contém os atributos preço inicial, preço por hora e lista de veículos. 
Foi implementado os métodos Cadastrar, Remover, Listar e Atualizar placa de um veículo.
Foi implementado o metódo "VerificaPlacaValida", que utilizando de uma expressão regular REGEX, é válidado se a placa segue o formato (AAA-1234).

## Classe Main
Foi implementado um menu iterativo, além de inserido as váriavéis de preco_inial e preco_por_hora que terão seus valores lidos pelo usuário e então após será enviado por parâmetro para o nosso objeto Emprestimo aqui instanciado.

## Detalhes
### Ao ser iniciada e pedido o preço inicial (preço cobrado ao entrar no estacionamento) e o preço por hora (preço cobrada por hora no estacionamento)
![image](https://github.com/Lucasgyn94/SistemaEstacionamentoDotnet/assets/91031320/144f078e-35a1-43fa-bf2c-388a17c7b466)

### Após e exibido um menu iterativo ao nosso usuário, em que temos a opção de Cadastrar, Remover, Listar e Atualizar um veículo pela placa de um veículo, além da opção de sair do programa.
![image](https://github.com/Lucasgyn94/SistemaEstacionamentoDotnet/assets/91031320/9c0cde55-61c7-4d32-adb6-f0f19e28530c)

### Caso seja solicitada a opção 1, o nosso sistema irá pedir uma placa válida ao nosso usuário no padrão (AAA-1234), e caso seja digitada uma placa nessa padrão e informadado para pressionar qualquer tecla para continuar.
![image](https://github.com/Lucasgyn94/SistemaEstacionamentoDotnet/assets/91031320/c198cb17-57cb-4c60-8a7e-7c5b0437a6b8)

### Caso a placa não seja no padrão previamente atríbuida na função que verifica se uma placa é válida atráves de expressões regulares REGEX, será retornado um aviso de placa inválida, e mostrando ao nosso usuário o padrão correto a ser cadastrado.
![image](https://github.com/Lucasgyn94/SistemaEstacionamentoDotnet/assets/91031320/4fe129c5-5a1e-464e-a51f-5460565fb0b1)

### Após o cadastro de um veículo pela sua placa, podemos ve-la selecionando a opção 3:
![image](https://github.com/Lucasgyn94/SistemaEstacionamentoDotnet/assets/91031320/1488aad3-0166-449f-bdc6-33228bc49d46)

### Também é possível atualizar a placa do veículo passando a placa e nova placa do veículo
![image](https://github.com/Lucasgyn94/SistemaEstacionamentoDotnet/assets/91031320/a4594f2c-358b-40e3-bccb-5831e076ed40)

### E por fim é possível remover um veículo passando a sua placa e gerando o valor a ser pago pelo cliente ao utilizar o estacionamento informando a quantidade de horas que o mesmo ficou
![image](https://github.com/Lucasgyn94/SistemaEstacionamentoDotnet/assets/91031320/7dfd2fcd-f3c5-4573-ba78-30722e5b66ac)

