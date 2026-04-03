<!-- 
EM CONSTRUÇÃO

-->
# Especificação de Requisitos e Priorização

Este documento apresenta a consolidação dos requisitos levantados durante os 5 dias de Design Sprint. A estrutura utiliza o modelo FURPS+ para categorização técnica e a técnica MoSCoW para definição de prioridade de implementação. 

## Requisitos funcionais 

| ID | Nome | Descrição | Prioridade
| :--- | :--- | :--- | :--- | Must 
| ID | Nome | Descrição |
| :--- | :--- | :--- |
| RF01 | Movimentar o avatar | O sistema deve processar entradas WASD para deslocar avatar 2D. | Must
| RF02 | Exibir Resíduos | O sistema deve permitir a visualização de objetos coletáveis (lixo) no mapa. | Must
| RF03 | Coletar Itens | O sistema deve remover objeto do cenário e adicionar ao inventário após colisão/ação. | Must
| RF04 | Processar Depósito/Reciclagem | O sistema deve validar proximidade à lixeira para descarregar itens. | Must
| RF05 | Gerar crafting | O sistema deve criar novos itens úteis ou decorativos ao atingir metas de resíduos coletados. | Must
| RF06 | Gerir progresso | O sistema deve gerenciar a transição entre as fases de limpeza, replantio e reconstrução do cenário. | Must
| RF07 | Interagir com o cenário | O sistema deve permitir interação com objetos e cenários.| Must
| RF08 | Reciclar resíduos | O sistema deve possuir um sistema de reciclagem (máquina única).| Must
| RF09 | Desbloquear recursos | O sistema deve possuir progressão baseada em desbloqueio de novos recursos.| Must
| RF10 | Utilizar ferramentas | O sistema deve permitir uso de ferramentas (machado, picareta, pá).| Must
| RF11 | Fertilizar o solo | O sistema deve permitir agricultura com uso de adubo.| Should


## Requisitos não funcionais

| ID | Nome | Descrição | Prioridade
| :--- | :--- | :--- | 
| RNF01 | Padronizar a tecnologia | Implementar em Godot. |
| RNF02 | Adotar estética visual | O sistema deve apresentar gráficos em estilo Pixel Art com sprites de baixa resolução. |
| RNF03 | Garantir a integridade | O sistema deve manter o histórico de versões e a documentação técnica centralizada e íntegra no GitHub Pages. |


## historico de versão 

| Versão |    Data    |          Descrição          |         Autor                               |       Revisor                                      |
| :----: | :--------: | :-------------------------: | :-----------------------------------------: | :------------------------------------------------: |
|  1.0   | 12/04/2025 | Criação do documento        | [Heyttor Augusto](https://github.com/H3ytt0r62) |  |
|  1.1   | 03/04/2026 | Padronização e edição dos Requisitos seguindo FURPS+ Moscow        | [Yasmin Abdon](https://github.com/yaabdon) |  |
