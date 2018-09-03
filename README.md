# Kanban

## Legenda
* Board = Kanban completo. Um kanban completo possui: members, lists, cards e labels
* Member = Membro do board, alguém que tem atividades na sprint
* List = Lista de cards
  * Backlog = Lista das atividades que serão priorizadas, estimadas e atribuídas para os members
  * Sprint = Lista de atividades alocadas aos members para realizar durante a sprint
  * Doing = Lista de atividades que estão sendo realizadas naquele momento
  * Done = Lista de atividades concluídas na sprint
* Card = Uma atividade que dura no mínimo 2h e no máximo 30h
* Label = Rótulos aplicáveis aos cards. Todo card na list Sprint, Doing e Done deve ter no mínimo um label do tipo Tarefa e podem ter os outros labels.
  * Tarefa Grande - 30h - 5d
  * Tarefa Média - 15h - 2.5d
  * Tarefa Pequena - 6h - 1d
  * Extra Sprint
  * Crítico
  * Impedido

## List Backlog
* Qualquer member pode cadastrar cards nessa list desde que pelo menos dois member concordem com a criação do card
* Qualquer member pode se candidatar para realização dos cards, mas a atribuição final acontecerá apenas na cerimônia de Sprint Planning
* Qualquer member pode estimar o tempo para realização dos cards, mas a estimativa final acontecerá apenas na cerimônia de Sprint Planning

## List Sprint
* Todos os members devem ter cards nessa list.
* Todos os cards dessa list devem estar atribuídos aos members.
* Todos os cards dessa list devem ter no mínimo um label do tipo Tarefa e podem ter os outros labels.
* As estimativas de tempo de realização dos cards atribuídos aos members devem totalizar o tempo de alocação do member.
* Cards são adicionados nessa list apenas na cerimônia de Sprint Planning.
* Cards com o label de Extra Sprint podem ser adicionados nessa list, mas nesse caso já devem ter sido estimadas e atribuídas a um member.
* Sempre que um card com label Tarefa Grande - 30h - 5d estiver atribuído a um member ele deverá criar outros cards com estimativas de Tarefa Pequena referenciando o card principal na descrição dos demais cards.
* Um member pode ter mais cards do que o seu tempo total de alocação na sprint.

## List Doing
* Todo member deve ter um e somente um card sem label de impedimento nessa list. Isso indica claramente que o member só pode realizar um card por vez.
* Todos os cards dessa list devem ter no mínimo um label do tipo Tarefa e podem ter os outros labels.

## List Done
* Todos os members devem ter cards nessa list.
* Todos os cards dessa list devem estar atribuídos aos members.
* Todos os cards dessa list devem ter no mínimo um label do tipo Tarefa e podem ter os outros labels.

## Procedimento para aplicar label Impedimento em um card
1. Escrever um comentário na atividade informando o motivo pelo qual está impedida.
1. Aplicar o label Impedido.
1. Mover o card para a list Sprint.

## Procedimento para remover o label Impedimento em um card
1. Escrever um comentário na atividade informando o que foi feito para resolver o impasse.
1. Remover o label Impedido.
