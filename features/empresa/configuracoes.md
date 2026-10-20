---
layout: default
title: "Configurações"
---

# Configurações

Configurações reúne as opções compartilhadas e as específicas de cada módulo, dentro de Empresa. As opções dos módulos ficam em subpáginas ou formulários próprios. Apenas regras que precisam variar entre empresas são configuráveis; regras centrais permanecem fixas.

## Configurações compartilhadas

| Item | Regra |
| --- | --- |
| Dados da empresa | Compartilhados entre as áreas de negócio. |
| Formas de pagamento | Pix, cartão de crédito, cartão de débito, dinheiro, boleto e transferência, em todos os planos; a empresa escolhe quais aceita, mantendo ao menos uma ativa. |
| Moeda | Reais (BRL), sem seleção de moeda. |
| Fuso horário | Sem configuração neste escopo. |

## Configurações por área

A configuração abaixo pertence ao plano Pro da respectiva área:

| Plano | Configuração | Efeito |
| --- | --- | --- |
| Serviços Pro | Dias e horários de atendimento | Define os períodos de atendimento usados pela agenda para agendamentos por horário. |

Vendas e Aluguéis não possuem configurações de módulo neste escopo.

## Vendas

| Item | Regra |
| --- | --- |
| Numeração | Automática. |
| Situação do pedido | Regras fixas de entrega, pagamento e cancelamento. |
| Controle de estoque | Definido por produto. Vender sem saldo é sempre permitido e pode deixar o saldo negativo. |
| Taxa de entrega | Sem valor padrão; cada venda começa em R$ 0,00. |
| Comprovantes | Impressão e envio no Vendas Pro, com os dados da empresa. |

Configurações de impostos e numeração fiscal ficam fora deste escopo, até que exista uma integração fiscal definida.

## Serviços

| Item | Regra |
| --- | --- |
| Etapas | Fixas: Aguardando, Em andamento, Aguardando cliente, Concluída e Cancelada; Em análise e Aprovada no Serviços Pro. |
| Prioridades | No Serviços Pro, opções fixas: Normal, Alta e Urgente. |
| Duração estimada | Opcional, definida por serviço, sem tempo padrão global. |

Checklists ficam fora deste escopo. Caso sejam incluídos futuramente, serão vinculados ao serviço ou a modelos reutilizáveis.

## Aluguéis

| Item | Regra |
| --- | --- |
| Período de cobrança | Definido por item: minuto, hora, dia, semana ou mês. |
| Contagem de diárias | Fixa: do dia 10 ao dia 13 são três diárias, sem cobrança pelo dia da devolução. |
| Disponibilidade | Não permite comprometer mais unidades do que as disponíveis; regra não pode ser desativada. |
| Atraso | Prazo de devolução passou e os itens ainda não foram devolvidos. |
| Multas e adicionais | Valor e motivo registrados no aluguel, sem multa automática; na devolução atrasada, o sistema sugere a cobrança dos períodos extras. |
| Caução | Etapa futura: valor opcional por aluguel, sem configuração global. |

Tempo mínimo por item e checklists de vistoria ficam fora do escopo definido.
