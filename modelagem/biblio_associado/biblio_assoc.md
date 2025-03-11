# Modelagem de biblioteca para empréstimo de livros

## Regra de Negócio / Requisitos
Uma biblioteca pretende controlar o empréstimo de livros, os dados
armazenados sobre cada biblioteca são, código, descrição e endereço,
uma biblioteca pode ter vários associados, e vários livros cadastrados,
uma mesma pessoa pode ser cadastrado em várias bibliotecas, no em
tando cada livro pode pertencer a uma biblioteca, empréstimos só serão
realizados para associados cadastrados, todo associado deve ter
matricula, nome e sexo. Os livros possuem ISBN e título. Em um dado
momento um livro só pode ser emprestado a um associado porém um
associado pode não pegar livros emprestados, mas também pode pegar
vários livros. Um livro pode ser escrito por vários autores e o mesmo
autor pode escrever vários livros, os dados dos autores, são, código e
nome. Um livro pode abordar muitos assuntos e um assunto pode ser
abordado por vários livros. Os dados de assunto são, código e
descrição.


# Modelo Conceitual (DER 1.0)

![Questao1](../../Imagem/DER/3.%20sem%20cardinalidade.png)

# Modelo Conceitual (DER 1.1)

Incluindo cardinalidades pertinentes a regra de negocio de forma a atender os
requisitos do sistema.

![Incluindo cardinalidades1](../../Imagem/DER/3.%20atividade%20biblioteca%20associados.png)

# Modelo Conceitual (DER 1.2)

Desmembrando relacionamentos n:m (muitos para muitos), evitando anomalias futuras.

![Incluindo entidades associativas](../../Imagem/DER/3.%20entidades%20associativas.png)

[Voltar](../../README.md)