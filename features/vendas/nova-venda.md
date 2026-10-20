---
layout: default
title: "Nova venda"
---

# Nova venda

O registro da venda reúne produtos, cliente, entrega, pagamento e valores no mesmo fluxo. Está disponível nos planos Vendas e Vendas Pro.

## Produtos

| Recurso | Uso |
| --- | --- |
| Busca | Nome. |
| Filtro | Categoria, na ordem definida em Categorias. |
| Itens | Definir quantidade, alterar o preço unitário, aplicar desconto no item ou remover da venda. |
| Atalhos | Editar o produto ou alterar seu estoque sem sair da venda. |

A falta de saldo não impede a venda: o produto sem estoque é sinalizado, mas pode ser adicionado.

## Cliente e vendedor

| Informação | Opções | Plano |
| --- | --- | --- |
| Cliente | Selecionar um cadastro, usar Consumidor final ou cadastrar um cliente na hora. | Vendas e Vendas Pro |
| Vendedor | Selecionar um membro ativo da equipe, mesmo sem conta. | Vendas Pro |

## Entrega

A venda é para entrega ou retirada. Consumidor final permite apenas retirada. A entrega exige um cliente cadastrado e endereço, que pode ser cadastrado na hora e fica salvo no cliente.

O endereço principal é selecionado primeiro; se não houver, é usado o primeiro cadastrado. É possível escolher outro endereço, e essa escolha é mantida ao editar outras informações. Ao trocar o cliente, o endereço é atualizado para o novo cadastro, com aviso para conferi-lo. Sem endereço válido, é preciso informar um antes de registrar a entrega. A troca de cliente preserva itens, descontos, pagamento e observações.

A taxa de entrega começa em R$ 0,00 e pode ser alterada na venda.

## Valores

| Informação | Conteúdo ou regra |
| --- | --- |
| Resumo | Subtotal, desconto, taxa de entrega e total. |
| Desconto | Por item e no pedido, em valor ou percentual; não pode superar o subtotal. |

Nome, unidade e preço dos produtos são preservados no pedido. Alterar o preço na venda não muda o preço do catálogo. Quando há cliente, seus dados são preservados conforme registrados na venda.

## Pagamento

Entrega e pagamento são independentes. Uma venda só está concluída quando foi entregue e está totalmente paga.

| Recurso | Funcionamento | Plano |
| --- | --- | --- |
| Formas de pagamento | Pix, cartão de crédito, cartão de débito, dinheiro, boleto e transferência, conforme as formas aceitas pela empresa. | Vendas e Vendas Pro |
| Pagamento único | Pago de uma vez ou em recebimentos parciais com data, sem vencimento. | Vendas e Vendas Pro |
| Parcelado | Entrada opcional, com forma e data de recebimento, e o número de parcelas que for preciso. No cartão de crédito, a venda conta como paga; nas demais formas, as parcelas partem de uma data de início, têm valor e vencimento editáveis e ficam a receber. | Vendas e Vendas Pro |
| Pagamento pendente | É possível registrar a venda sem pagamento; valores não pagos permanecem pendentes. | Vendas e Vendas Pro |
| Troco | Calcula o troco em dinheiro e o registra na observação do pagamento. | Vendas Pro |

## Ações

| Ação | Finalidade |
| --- | --- |
| Registrar venda | Firmar a venda com os dados informados. |
| Cancelar preenchimento | Sair do registro; se houver alterações não salvas, confirmar se deseja descartá-las ou continuar editando. |

A venda registrada baixa o estoque dos produtos com controle ativo, mesmo que o saldo fique negativo.

Ao alternar entre produtos e pedido, os dados preenchidos são mantidos. Se houver falha ao salvar, o preenchimento é preservado para nova tentativa. Repetir o envio não duplica a venda nem seus recebimentos. Se a venda tiver sido alterada em outro lugar, é preciso atualizar e revisar os dados antes de salvar. Essas proteções valem nos dois planos e não dependem de rascunhos salvos.

É possível incluir até 200 itens por venda, com quantidades fracionadas para unidades como peso, volume e comprimento.

## Recursos Pro

No plano Vendas Pro:

| Recurso | Descrição |
| --- | --- |
| Rascunho | Salvar para continuar depois. |
| Orçamento | Salvar como [orçamento](orcamentos.html), preservando os dados sem baixar estoque nem contabilizar receita. |

Para uma etapa futura do Vendas Pro, estão previstos produtos recentes e favoritos e observações por item.
