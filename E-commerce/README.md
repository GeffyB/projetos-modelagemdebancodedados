# Projeto de Banco de Dados para E-Commerce
Projeto conceitual do desenvolvimento de um Banco de Dados para um E-Commerce. Projeto solicitado como atividade prática do curso de Banco de Dados SQL e NoSQL.  
O projeto foi modelado Usando a Ferramenta de Diagramação MySQL Workbench da Oracle.  

#
## Narrativa do projeto:

#
Produto:  
 - Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros);  
 - Cada produto possui um fornecedor;  
 - Um ou mais produtos podem compor um pedido.  

Cliente:  
 - O cliente pode se cadastrar no site com seu CPF ou CNPJ;
 - O Endereço do cliente irá determinar o valor do frete;
 - Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto.  

Pedido:  
 - O pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega;
 - Um produto ou mais compoem o pedido;
 - O pedido pode ser cancelado.

Fornecedor & estoque:  
**Critérios não determinados**  

#

## Proposta de refinamento do Banco de Dados:

#
Foi sugerido os seguintes ajustes/adições ao projeto:
 - Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;  
 - Pagamento – Pode ter cadastrado mais de uma forma de pagamento;  
 - Entrega possui status e código de rastreio.








