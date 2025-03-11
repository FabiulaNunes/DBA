# Aula de Markdown
---
## Titulo 2
### Titulo 3
#### Titulo 4
##### Titulo 5
###### Titulo 6

## Paragrafo
---
<!-- comentario -->

Paragrafo

Segundo paragrafo

## Listas
---

### Listas Nao Ordenadas

- Item 1
* Item 2
    - Item 2.1
        - Item 2.1.1
- Item 3

### Listas Ordenadas

1. Primeiro item
1. Segundo item
    1. sub item
    1. sub item 2
        1. sub item 2.1
1. Terceiro item

### Listas de Tarefas

- [X] Conceitos de banco
- [ ] Aula de markdown

## Tabela
---

| Codigo | Nome | Endereco |
|:-:|-|:-:|
| 01 | Maria | Taguatinga |
| 02 | Joao | Samambaia |

## Links e Imagens
---

[Clique aqui](https://www.sistemafibra.org.br/senai/)

![Logo do senai](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRpheYOwcfpdRNxoB2d09hFsOGz0144RwU6ih3jjA6uU0_NWsj9cKPAPJaxKxlCRdTikA&usqp=CAU)

![Logo senai azul](./)

Veja mais sobre a [Modelagem Conceitual](./modelagemConceitual.md)


## Citação
---
> Simbolo para fazer Citação 

> Ex: "Se esta caro nao compra!"

## Codigo
---
### Codigo Inline

Isso é um Hello World em Python `print("Hello World")`

### Codigo em Bloco

```PYTHON

idade = 18
if (idade >= 18):
   print("Você é maior de idade")

```

```SQL

CREATE DATABASE senai
IF NOT EXISTS;

```

## Marcadores
---
_Este é um texto em Italico_

__Negrito__

___Italico e Negrito___