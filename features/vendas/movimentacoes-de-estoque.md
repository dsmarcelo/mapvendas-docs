---
layout: default
title: "Movimentações de estoque"
---

# Movimentações de estoque

O histórico de movimentações fica no produto, dentro de Produtos, nos planos Vendas e Vendas Pro, sem entrada própria na navegação principal.

## Histórico

| Grupo | Informações |
| --- | --- |
| Identificação | Data, produto e tipo. |
| Alteração | Quantidade e saldos antes e depois. |
| Rastreabilidade | Origem e autor da alteração. |

As movimentações são imutáveis: o histórico não é apagado ou reescrito para corrigir o saldo. Uma correção gera uma nova movimentação.

## Tipos

| Tipo | Efeito |
| --- | --- |
| Entrada | Aumenta o saldo. |
| Saída | Diminui o saldo; pode deixá-lo negativo. |
| Definir | Ajusta o saldo para a quantidade contada. |
| Venda | Baixa o saldo dos produtos com controle ativo. |
| Edição de venda | Lança a diferença de itens ou quantidades alterados no pedido. |
| Cancelamento de venda | Devolve as unidades anteriormente baixadas. |

A pessoa atribuída à operação e a conta que registrou a alteração são informações distintas.

## Funcionalidades previstas

No plano Vendas Pro:

| Recurso | Descrição |
| --- | --- |
| Movimentações adicionais | Devoluções, transferências, perdas e reservas de estoque. |

Orçamentos não geram reservas de estoque.
