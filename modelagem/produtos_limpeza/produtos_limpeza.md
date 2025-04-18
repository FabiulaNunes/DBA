# Modelagem para controle de produtos de limpeza

## Regra de Negócio / Requisitos
Uma firma vende produtos de limpeza, e deseja melhor controlar os
produtos que vende, seus clientes e os pedidos. Cada produto é
caracterizado por um código, nome do produto, categoria (ex:
detergente, sabão em pó, sabonete, etc), e seu preço. A categoria é uma
classificação criada pela própria firma. A firma possui informações sobre
todos seus clientes. Cada cliente é identificado por um código, nome,
endereço, telefone, status ("bom", "médio", "ruim"), e o seu limite de
crédito. Guarda-se igualmente a informação dos pedidos feitos pelos
clientes. Cada pedido possui um número e guarda-se a data de
elaboração do pedido. Cada pedido pode envolver de um a vários
produtos, e para cada produto, indica-se a quantidade deste pedida.

# Modelo Conceitual (DER 1.0)

![Questao1](../../Imagem/DER/8.%20sem%20cardinalidade.png)

# Modelo Conceitual (DER 1.1)

Incluindo cardinalidades pertinentes a regra de negocio de forma a atender os
requisitos do sistema.

![Incluindo cardinalidades](../../Imagem/DER/8.%20produtos%20de%20limpeza.png)

# Modelo Conceitual (DER 1.2)

Desmembrando relacionamentos n:m (muitos para muitos), evitando anomalias futuras.

![Incluindo entidades associativas](../../Imagem/DER/8.%20entidade%20associativa.png)

[Voltar](../../README.md)