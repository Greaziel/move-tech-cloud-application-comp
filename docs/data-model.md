#Modelo de dados 

A Api tem duas entidades: pedidos (orders) e seus Itens (Itens), ligadas por um relacionamento 1:N

##Tabela: orders

| Coluna    | Tipo   (SQLAlchemy)     | Tipo (PostgreSQL) | Restricoes 
|-----------|-------------------------|-------------------|------------
| id        |  String 


##Tabela: Itens 


| Coluna    | Tipo   (SQLAlchemy)     | Tipo (PostgreSQL) | Restricoes 
|-----------|-------------------------|-------------------|------------
| id        |  String 



# Relacionamento 

Um pedido tem vários Itens (1:N) A chave estrangeira xxx fica na tabela xxxx


O relcacionamento está declaraco com CASCADE o que significa que xxxxx