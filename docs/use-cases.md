# Casos de uso

## UC01 — Registrar entrada

**Ator:** Funcionário, Gerente ou Administrador

**Pré-condições:**
- Usuário deve estar autenticado.
- Usuário deve possuir permissão para registrar entradas.
- Produto deve estar cadastrado.

**Fluxo principal:**
1. Usuário seleciona o produto.
2. Usuário informa a quantidade.
3. Usuário informa o motivo da entrada.
4. Sistema valida os dados.
5. Sistema verifica as permissões do usuário.
6. Sistema registra a movimentação de entrada.
7. Sistema atualiza a quantidade disponível do produto.
8. Sistema registra o usuário responsável e a data da movimentação.

**Resultado:**
- A quantidade do produto é incrementada.
- A movimentação fica registrada no histórico.

## UC02 — Registrar saída
- Realizar login no sistema
- Selecionar produto
- Informar quantidade
- Informar motivo
- Sistema verifica estoque
- Sistema verifica privilegios
- Sistema registra movimentação
- Sistema atualiza estoque