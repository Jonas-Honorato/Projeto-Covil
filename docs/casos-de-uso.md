# 🎯 Casos de Uso – Projeto Covil

Descrição dos principais fluxos de uso do sistema.

---

## UC01 – Registrar Pedido
**Ator Principal:** Funcionário  
**Fluxo Principal:**
1. Funcionário acessa a tela de pedidos.
2. Seleciona os itens (hambúrguer, batata, bebida).
3. Confirma o pedido.
4. Sistema salva o pedido no banco de dados.
5. Sistema gera e envia a comanda para impressão.
6. Sistema atualiza o estoque.

---

## UC02 – Consultar Estoque
**Ator Principal:** Gerente  
**Fluxo Principal:**
1. Gerente acessa a tela de estoque.
2. Visualiza lista de ingredientes e quantidades.
3. Sistema exibe alerta de estoque baixo (se houver).

---

## UC03 – Gerar Relatório
**Ator Principal:** Gerente  
**Fluxo Principal:**
1. Gerente escolhe o período (ex.: última semana).
2. Sistema gera relatório de vendas e produtos mais pedidos.
3. Gerente pode exportar relatório para PDF.
