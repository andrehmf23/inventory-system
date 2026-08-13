# Banco de Dados

## Usuários

- id
- nome
- email
- senha_hash
- papel
- status

## Produtos

- id
- nome
- sku
- categoria_id
- fornecedor_id
- preco_custo
- estoque_minimo
- status

## Estoque

- id
- produto_id
- quantidade

## Categorias

- id
- nome

## Movimentações

- id
- produto_id
- usuario_id
- tipo
- motivo
- quantidade
- data

## Fornecedores

- id
- nome