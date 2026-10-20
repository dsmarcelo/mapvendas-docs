---
layout: default
title: "Estoque"
---

# Estoque

O estoque dos produtos de venda fica integrado à lista de [Produtos](produtos.html), sem página própria. Disponível nos planos Vendas e Vendas Pro.

## Controle por produto

O controle é ativado individualmente por produto, com saldo inicial zero ou com o estoque inicial informado no cadastro. Desativá-lo pausa o controle sem apagar o saldo; reativá-lo retoma o saldo anterior.

O produto está com estoque baixo quando seu saldo é menor ou igual ao limite definido no cadastro.

A venda nunca é bloqueada por falta de saldo, e o saldo pode ficar negativo. O produto sem estoque é sinalizado na lista e na nova venda.

## Operações

| Operação | Efeito |
| --- | --- |
| Entrada | Soma uma quantidade ao saldo. |
| Saída | Subtrai uma quantidade do saldo. |
| Definir | Substitui o saldo pela quantidade contada. |
| Venda | Baixa pela venda registrada. |
| Edição de venda | Lança a diferença quando itens ou quantidades do pedido mudam. |
| Cancelamento de venda | Devolve as unidades baixadas pelo pedido. |

Entrada, saída e definir são feitas pela lista de Produtos ou pelo card do produto na nova venda. Antes de confirmar, são mostrados o saldo atual e o saldo previsto. Entrada e Saída exigem quantidade maior que zero; Definir aceita zero ou mais. Se o saldo previsto ficar negativo, um aviso permite continuar. Em produtos sem controle, somente Definir está disponível, e confirmar ativa o controle.

As alterações preservam o histórico em [Movimentações de estoque](movimentacoes-de-estoque.html).

## Funcionalidades previstas

No plano Vendas Pro:

| Recurso | Descrição |
| --- | --- |
| Consulta | Valor do estoque, quantidades reservadas e saldo por localização. |
| Filtros | Excesso e movimentação recente. |
| Operações | Transferências e inventário. |

Orçamentos não reservam nem baixam estoque.
