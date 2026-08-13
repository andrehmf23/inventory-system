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

**Ator:** Funcionário, Gerente ou Administrador

**Pré-condições:**
- Usuário deve estar autenticado.
- Usuário deve possuir permissão para registrar saídas.
- Produto deve estar cadastrado.

**Fluxo principal:**
1. Usuário seleciona o produto.
2. Usuário informa a quantidade.
3. Usuário informa o motivo da saída.
4. Sistema valida os dados.
5. Sistema verifica as permissões do usuário.
6. Sistema verifica se existe quantidade suficiente em estoque.
7. Sistema registra a movimentação de saída.
8. Sistema atualiza a quantidade disponível do produto.
9. Sistema registra o usuário responsável e a data da movimentação.

**Resultado:**
- A quantidade do produto é decrementada.
- A movimentação fica registrada no histórico.