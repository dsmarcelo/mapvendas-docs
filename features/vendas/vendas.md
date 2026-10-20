---
layout: default
title: "Vendas"
---

# Vendas

A página reúne os pedidos de venda da empresa, com acesso ao detalhe e à edição de cada pedido.

## Lista e filtros

| Recurso | Conteúdo | Plano |
| --- | --- | --- |
| Lista | Número, hora, cliente, itens, entrega, pagamento e total, agrupados por dia. | Vendas e Vendas Pro |
| Recortes | Abertos, a receber, concluídos e todos. | Vendas e Vendas Pro |
| Filtros | Período, cliente e entrega; busca por cliente ou número. | Vendas e Vendas Pro |
| Resumo | Vendas do período, valores a receber e pedidos a entregar. | Vendas e Vendas Pro |
| Vendedor | Identificação na lista e filtro por vendedor. | Vendas Pro |
| Filtros avançados | Pagamento, canal e valor. | Vendas Pro |

A lista começa nos últimos 7 dias. Ao abrir **A receber**, começa em **Todo o período**, incluindo vendas antigas e pagamentos sem vencimento; é possível escolher outro período. Vendas com parcelas vencidas aparecem primeiro. Vendas canceladas ou totalmente pagas não entram nessa consulta.

## Situação da venda

Entrega e pagamento são fatos independentes. A conclusão é calculada quando a venda está entregue (ou retirada) e totalmente paga, sem uma ação manual de concluir.

| Pagamento | Regra |
| --- | --- |
| Pago | Nada a receber. |
| Parcial | Pagamento único com parte recebida. |
| Pendente | Pagamento único sem nada recebido. |
| A vencer | Parcelas em aberto, nenhuma vencida; a lista mostra o próximo vencimento. |
| Vencido | Alguma parcela não paga após o vencimento; tem prioridade nas listas de trabalho. |

| Entrega | Regra |
| --- | --- |
| A entregar / Entregue | Venda com entrega. |
| Retirada / Retirado | Venda para retirada na loja. |

Orçamentos são um recurso do Vendas Pro e são tratados em [Orçamentos](orcamentos.html). Etapas opcionais como Preparando e Pronta não fazem parte do escopo atual.

## Detalhe e edição

| Informação | Conteúdo | Plano |
| --- | --- | --- |
| Detalhe | Itens, cliente, entrega, pagamento, observações e valores. | Vendas e Vendas Pro |
| Edição | Todos os dados do pedido podem ser alterados depois de registrado; mudanças nos itens ajustam o estoque. Mudanças no total exigem revisar o pagamento quando os valores deixam de corresponder à venda. | Vendas e Vendas Pro |
| Vendedor | Membro atribuído à venda. | Vendas Pro |

Pela lista ou pelo detalhe é possível receber pagamento, marcar como entregue ou retirado e cancelar.

## Pagamentos e cancelamento

Receber, revisar e cancelar pagamentos estão disponíveis nos dois planos, dentro da própria venda, sem depender do Financeiro. Antes de confirmar um recebimento, são apresentados o saldo atual, o valor informado, a forma de pagamento e o saldo que restará. Não é permitido receber mais do que o saldo pendente.

Um lançamento incorreto pode ser corrigido com **Cancelar pagamento**, após conferir e confirmar valor, forma e data, sem motivo obrigatório. Ele deixa de contar como recebido, preservando o histórico, e a parcela volta a ficar pendente quando aplicável. O sistema não devolve dinheiro ao cliente automaticamente.

A condição de pagamento só pode ser trocada quando não houver pagamentos ativos. Se uma edição alterar o total, os valores pendentes devem ser revisados até que recebimentos e saldo previsto correspondam ao novo total; pagamentos confirmados não são alterados automaticamente. Se o total ficar abaixo do recebido, é preciso cancelar os lançamentos incorretos antes de salvar. Sem condição definida, o valor continua integralmente pendente.

Cancelar exige um motivo (cliente desistiu, pedido duplicado, sem estoque ou outro, com descrição) e devolve ao estoque as unidades baixadas pelo pedido. Se houver pagamentos registrados, há uma confirmação adicional para conferir eventual devolução ao cliente. Cancelar a venda mantém os pagamentos no histórico e não devolve dinheiro automaticamente; não é necessário registrar um reembolso para cancelar. Uma venda cancelada não pode ser editada.

O histórico das operações é preservado; a consulta visual completa do histórico é um recurso Pro.

## Recursos Pro

No plano Vendas Pro:

| Recurso | Descrição |
| --- | --- |
| Indicadores | Faturamento e ticket médio. |
| Comprovante | Impressão e envio. |
| Operações | Devoluções e duplicação de vendas. |
| Acompanhamento | Rascunhos e apresentação visual do histórico. |
