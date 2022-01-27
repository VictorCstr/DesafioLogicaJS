Contexto: Fazemos parte de uma equipe de desenvolvimento de websites e fomos
contratados para a criação de um site de catálogo de produtos. Agora precisamos
definir algumas regras de negócio para nosso Comércio Eletrônico e para isso
precisamos definir algumas funcionalidades que podemos trabalhar usando Lógica
de Programação e Javascript.
Neste caso, vamos tratar de uma loja (fictícia) de artigos eletrônicos e de informática,
tudo bem?
E por conta disso, temos uma lista de produtos já declarada num arquivo Javascript
que vocês terão acesso. Cada produto tem a seguinte estrutura:

{
"codProduto": 25754,
"descricao": "ADAPTADOR BLUETOOTH USB RECEPTOR DE AUDIO P2",
"preco": 5.0,
"qtdEstoque": 10,
"disponivel": "sim",
"emDestaque": "sim",
"departamento": {
    "idDepto": 1,
    "nomeDepto": "Adaptadores"
    }
}

Pois bem, com esta estrutura, agora organizando os produtos em uma grande lista,
podemos (e é este o objetivo) criar várias funcionalidades para as regras de negócio
do nosso E-commerce. Então vamos lá.

Itens a serem resolvidos
1. Quantidade total de itens cadastrados em estoque (somatória das
quantidades de todos os produtos)
2. Quantidade total de itens em destaque (somatória das quantidades dos itens
marcados como "emDestaque : sim")
3. Quantidade total de itens disponíveis (similar ao anterior)
4. Quantidade de itens disponíveis e em destaque
5. Valor total do inventário da empresa (somatória dos valores individuais
multiplicado pela quantidade em estoque - considere apenas os produtos “EM
ESTOQUE”)
6. Produto mais caro da loja (bem como seu departamento - considere apenas o
preço dele)
7. Produto mais barato da loja (bem como seu departamento - considere apenas
o preço dele)
8. Produto com estoque mais valioso (considere o preço multiplicado pela
quantidade e também apenas EM ESTOQUE)
9. Produto com estoque menos valioso (considere o preço multiplicado pela
quantidade e também apenas EM ESTOQUE)
10. Valor do ticket médio dos produtos da empresa (basicamente o valor total do
inventário dividido pelo número de itens)
11. Somatória de itens por departamento (você deverá retornar um objeto
contendo o nome do departamento e o total de itens nele - Novamente
considere os produtos “EM ESTOQUE” - e é apenas a somatória da quantidade
de itens)
12. Valor total do inventário por departamento (similar ao item anterior -
considere TODOS os produtos)
13. Ticket médio por departamento (similar ao item anterior, porém retornando
uma lista de objetos que contenha o nome do departamento e o seu ticket
médio). Este é um exercício difícil, porém é descomplicado de ser realizado
tendo claro as demais saídas até então. Verifique a possibilidade de reutilizar
parte da programação ou sua lógica trabalhada.
14. Departamento mais valioso (qual o departamento que tem a maior somatória
dos valores dos itens - Considere todos os departamentos)
15. Departamento menos valioso (similar ao anterior)
