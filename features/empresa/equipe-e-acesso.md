---
layout: default
title: "Equipe e acesso"
---

# Equipe e acesso

Equipe reúne as pessoas que trabalham para a empresa, tenham ou não acesso ao sistema. O cadastro da equipe é compartilhado, mas seus recursos ficam limitados às áreas com Vendas Pro, Serviços Pro ou Aluguéis Pro, respectivamente.

## Disponibilidade por área

| Uso da equipe | Plano |
| --- | --- |
| Vendedor e recursos de equipe em Vendas | Vendas Pro |
| Responsável e recursos de equipe em Serviços | Serviços Pro |
| Responsável e recursos de equipe em Aluguéis | Aluguéis Pro |

A mesma pessoa pode atuar em mais de uma área, sem cadastros duplicados. A disponibilidade pelo plano e as permissões do papel são verificações independentes; uma permissão não libera um recurso fora do plano contratado.

Sem nenhum plano Pro, apenas o proprietário acessa a empresa, e convites pendentes não podem ser aceitos. Membros e histórico são preservados, e o acesso volta ao contratar um Pro. Os membros não veem as áreas sem Pro; apenas o proprietário acessa essas áreas, mesmo que o papel do membro permita.

## Lista

| Informação | Conteúdo ou regra |
| --- | --- |
| Identificação | Nome e cargo. |
| Status do membro | Ativo ou desativado. |
| Status do acesso | Ausente, convite pendente ou ativo. |
| Último acesso | Última atividade no sistema; aparece apenas para quem tem conta. |

## Membro

| Informação | Regra |
| --- | --- |
| Nome | Identificação do membro. |
| Cargo | Texto livre; não concede acesso nem permissões. |
| E-mail | Obrigatório apenas para convidar a pessoa a acessar o sistema. |

## Atribuições

Membros ativos podem ser selecionados como vendedor em vendas e responsável em aluguéis e serviços, mesmo sem conta.

Os registros preservam o membro atribuído após sua desativação. A pessoa atribuída e a conta que registrou cada alteração são informações distintas.

## Papéis e permissões

| Conceito | Regra |
| --- | --- |
| Papéis | Administrador, Gerente, Vendedor, Técnico e Atendente; apenas para membros com conta. |
| Permissões | Pertencem ao papel; personalização prevista para etapa futura. |
| Administrador | Acesso total, sem possibilidade de restrição. |

Alterar preço no pedido e alterar preço no catálogo são permissões independentes. Permitir negociar o preço de uma venda não concede permissão para mudar o preço usado nas próximas vendas.

| Módulo | Permissões |
| --- | --- |
| Vendas | Visualizar, criar, editar, alterar preço no pedido, alterar preço no catálogo e cancelar. |
| Estoque | Visualizar e ajustar. |
| Financeiro | Visualizar. |
| Serviços e Aluguéis | Visualizar, criar, editar e cancelar. |

Para alterar dados em um módulo, o papel também precisa da permissão de visualizar. Acesso a Financeiro não decorre de permissões de Vendas, Serviços ou Aluguéis.

## Convites e acesso

Ações realizadas pelo administrador:

| Ação | Efeito |
| --- | --- |
| Convidar | Enviar convite por e-mail e definir o papel; acesso começa após a aceitação. |
| Reenviar ou revogar | Gerenciar convites pendentes. |
| Remover acesso | Encerrar o acesso sem excluir o membro da equipe. |

## Desativação e histórico

| Ação | Efeito |
| --- | --- |
| Desativar | Impede novas atribuições e encerra o acesso, sem apagar o histórico. |
| Reativar | O administrador restaura o acesso que o membro possuía antes da desativação. |

Um membro não pode desativar a si mesmo. Não é possível remover, desativar ou rebaixar o último administrador.

## Funcionalidades previstas

Em Vendas Pro, Serviços Pro ou Aluguéis Pro, sempre limitadas à respectiva área:

| Recurso | Descrição |
| --- | --- |
| Unidades de atuação | Definem onde o membro pode ser atribuído e limitam o acesso de quem tem conta; o administrador acessa todas as unidades. |
| Unidades na equipe | Exibição na lista, definição no cadastro e no convite. |
| Personalização de permissões | O administrador ajusta o papel; a alteração afeta todos os membros com esse papel, exceto Administrador, que não pode ser restringido. |
| Histórico administrativo | Convites, mudanças de papel, unidades ou permissões e desativações registram autor e data. |
