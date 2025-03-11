# Modelagem de biblioteca para cadastrar livros

## Regra de Negócio / Requisitos
Uma biblioteca deseja manter informações sobre seus livros.
Inicialmente, quer armazenar para os livros as seguintes características:
ISBN, título, ano editora e autores deste livro. Para os autores, deseja
manter: nome e nacionalidade. Cabe salientar que um autor pode ter
vários livros, assim como um livro pode ser escrito por vários autores.
Cada livro da biblioteca pertence a uma categoria. A biblioteca deseja
manter um cadastro de todas as categorias existentes, com informações
como: código da categoria e descrição. Uma categoria pode ter vários
livros associados a ela.

# Modelo Conceitual (DER)

![Questao1](../../Imagem/DER/7.%20sem%20cardinalidade.png)

# Modelo Conceitual (DER 1.1)

Incluindo cardinalidades pertinentes a regra de negocio de forma a atender os
requisitos do sistema.

![Incluindo cardinalidades](../../Imagem/DER/7.%20biblioteca.png)

# Modelo Conceitual (DER 1.2)

Desmembrando relacionamentos n:m (muitos para muitos), evitando anomalias futuras.

![Incluindo entidades associativas](../../)

[Voltar](../../README.md)