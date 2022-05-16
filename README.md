# Banco-de-dados-Mario-Luigi
Atividade do curso de programação do proa, com objetivo de modelar um banco de dados
Enunciado da atividade: Uma seguradora para carros Mario & Luigi está trabalhando com alta demanda de serviços e precisa se modernizar para poder crescer com qualidade. A empresa não possui um banco de dados completo e faz diversas anotações em papel ou em Excel o que prejudica muito o gerenciamento das equipes, das receitas e dos recursos.
Como contratados vocês devem oferecer a eles uma solução digital de um banco e primeiro passo para isso é o planejamento desses dados: o que eles devem fazer? Como devem fazer? Quais são as principais informações?
Vamos elaborar um diagrama para uma seguradora de automóveis, tartarugas e encanamento residencial:
Entidades: Cliente, Apólice, Carro e Acidentes.

Explicação:
Abaixo o modelo conceitual da modelagem, esse é o modelo inicial, onde se atribui as entidades e seus atributos, como também as relações das entidades
Todas entidades tem como atributo um ID, pois é uma numeração unica, que não se repetira. Além do ID cada entidade tem seus proprios atributos, a exemplo, o cliente tem nome e cpf, já o carro tem marca e placa. No quesito das relações entre as entidades, temos como exemplo "Cliente" e "Carr", já que os 2 tem essa ligação, um cliente, nesse banco de dados, tem pelo menos um carro, e cada carro tem um cliente.
![Conceitual_1](https://user-images.githubusercontent.com/99970279/168680268-e22a3f35-30e4-4fb0-bcf2-df2a0501c332.png)

Partindo agora para o modelo logico, nesse modelo os atributos ficam dispostos em tabelas de acordo com suas entidades, é descrito qual tipo de campo será cada atributo, exemplo "INTEGER" é um campo que irá aceitar apenas numeros inteiros, util para o campo de telefone do cliente. Outra diferença desse modelo são as chaves primarias e estrangeiras. Chaves primarias são os IDs, pois são chaves unicas, como o Id_Apolice; Já as chaves estrangeiras são chaves que vem de outra entidade, por exemplo na tabela do Carro, tem 3 chaves estrangeiras, ID_Cliente, ID_Apolice, ID_Acidentes são chaves que já existem em tabelas, mas serão necessarias para entidade Carro também.
![Lógico_1](https://user-images.githubusercontent.com/99970279/168681757-a9984248-3530-490a-b5cb-be3937556da4.png)

