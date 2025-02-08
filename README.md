# Modelagem para E-commerce
## Desafio proposto para a modelagem de banco de dados para um E-commerce.
![image](https://github.com/user-attachments/assets/dce83624-5bf8-4ed6-a923-bac7d50cdbf7)

### O desafio foi dividido em duas partes
1. Primeiro iriamos fazer junto com a professora Juliana Mascarenhas a modelagem básica com as entidades solicitadas: Cliente, Fornecedor, Pedido, Produto e o Estoque.
2. Depois, sozinhos, iriamos refinar a modelagem ja iniciada com alguns critérios, sendo eles
     a. Cliente deveria poder colocar CNPJ ou CPF não podendo adicionar os dois;
     b. Poderia ser cadastrado mais de uma forma de pagamento;
     c. Na entrega deveria ter status e código de rastreio.

![image](https://github.com/user-attachments/assets/3b6bfda0-5cbb-420b-a801-aa4ee6fd9abc)

   
Na minha modelagem optei por criar duas entidades tanto para o CNPJ quanto para o CPF e o cliente poderia está ligado a somente uma delas. Também criei uma entidade para selecionar a formas de pagamentos onde geraria uma foreingh key no pedido. E por fim criei também a entidade entrega com os atributos necessarios que seriam refletidos no pedido.

Esse foi um ótimo desafio que me fez refletir muito em como conectar e tornar as entidades o mais fiel possivel para o posterior momento de desenvolvimento. 

#### Estou aberta a dicas de como tornar minha modelagem melhor!
   
