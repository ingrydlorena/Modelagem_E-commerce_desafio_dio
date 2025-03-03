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

   
Na minha modelagem, optei por criar duas entidades separadas para CNPJ e CPF, garantindo que o cliente estivesse vinculado a apenas uma delas. Também criei uma entidade para as formas de pagamento, gerando uma chave estrangeira na tabela de pedidos. Por fim, adicionei a entidade Entrega, com os atributos necessários que são refletidos nos pedidos.

Esse foi um ótimo desafio, que me fez refletir bastante sobre como conectar as entidades de forma lógica e consistente, garantindo uma estrutura fiel para o desenvolvimento posterior.

### Estou aberta a sugestões de como aprimorar ainda mais minha modelagem!

# Segunda Parte do Projeto
### Construindo seu primeiro projeto lógico de banco de dados
O desafio consistia em replicar a estrutura apresentada pela professora, adicionando melhorias e personalizações. Fiz ajustes recomendados, refinando o modelo inicial ao remover redundâncias e aprimorar o fluxo dos dados. O foco do projeto é um sistema de dropshipping, onde o cliente compra de um vendedor, mas a entrega é feita pelo fornecedor.

Para otimizar análises, criei consultas SQL que permitem calcular o total vendido por vendedor, identificar vendedores que também são fornecedores, contar pedidos por forma de pagamento e listar a relação entre produtos, fornecedores e estoques.

### Ainda há pontos para melhorar, como o controle automático de reposição de estoque, relatórios gerenciais para análise de vendas e um rastreamento mais detalhado das entregas. O projeto segue em evolução para tornar o sistema mais eficiente.
   
