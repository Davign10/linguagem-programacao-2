# Linguagem-Programacao-2

## Exercício 1 - Com base no diagrama de classes abaixo, implemente um projeto orientado a objetos contendo as abstrações representadas e considerando as seguintes instruções:
- Package: edu.fatec.lp2.exercicio1 (organizar as classes e outros pacotes dentro deste)
- Contatos e mensagens são Arrays inicializados via construtor;
- Todos os atributos são privados;
- A classe abstrata Mensagem deve possuir um método abstrato Mensagem sendMessage(String); e
- Mensagem sendMessage(String) deve retornar a sua própria instância.

![ex01-lp2](https://user-images.githubusercontent.com/101421659/232364087-95a76477-78d1-447a-8df1-a9ec2afb6a00.PNG)

-----------------

## Exercício 2 - Seu Astolfo recentemente adquiriu uma rede de supermercados e contratou a Você S.A., empresa especializada no desenvolvimento de soluções informatizadas, para implementar uma prova de conceito referente ao seu domínio de compras. Para isso ele considerou as seguintes regras como sendo suas necessidades:

- Package: edu.fatec.lp2.exercicio2 (organizar as classes e outros pacotes dentro deste)
- Deve haver uma abstração simplificada que represente seu Supermercado;
- Deve haver uma abstração que represente seu produto, conforme diagrama abaixo;
- A abstração produto terá seus próprios atributos e um único comportamento para retornar seu nome;
- Deve haver uma abstração para representar os itens comprados pelo cliente;
- Cada item de compra terá a quantidade adquirida e um desconto que pode variar de 0 ao descontoMaximo;
- Deve haver a possibilidade de vincular ao item de compra o produto e o desconto;
- Só será possível associar um único produto ao item de compra;
- Deve haver uma ação no item de compra que possibilite calcular seu preço independente dos demais;
- Deve haver uma abstração que represente a lista de compras e o mesmo deve possuir uma quantidade limite;
- Deve haver uma ação na lista de compras que possibilite adicionar itens de compra até seu limite;
- Deve haver uma ação na lista de compras que calcule o preço total da lista de compras; e
- As abstrações de item de compra e lista de compra deverão respeitar uma interface comum.

![ex02-lp2](https://user-images.githubusercontent.com/101421659/232364191-73956815-ca2f-4bfc-970b-207ac70305cc.PNG)

