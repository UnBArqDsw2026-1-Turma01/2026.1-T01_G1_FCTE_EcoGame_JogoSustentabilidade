<!-- 
EM CONSTRUÇÃO

-->
# Especificação de Requisitos e Priorização

Este documento apresenta a consolidação dos requisitos levantados durante os 5 dias de Design Sprint. A estrutura utiliza o modelo FURPS+ para categorização técnica e a técnica MoSCoW para definição de prioridade de implementação. 

## Requisitos Funcionais

| ID | Nome | Descrição | Prioridade |
| :--- | :--- | :--- | :--- |
| RF01 | Movimentar o avatar | O sistema deve processar entradas WASD para deslocar o avatar 2D pelo mapa. | Must |
| RF02 | Exibir resíduos | O sistema deve permitir a visualização de objetos coletáveis (lixo) distribuídos no mapa. | Must |
| RF03 | Coletar itens | O sistema deve remover o objeto do cenário e adicioná-lo ao inventário após ação/colisão do avatar. | Must |
| RF04 | Animar coleta (on click) | O sistema deve acionar a animação de coleta do avatar ao clicar/interagir com um item coletável. | Must |
| RF05 | Processar depósito/reciclagem | O sistema deve validar a proximidade à maquininha de reciclagem para processar e transformar itens do inventário. | Must |
| RF06 | Sistema de craft | O sistema deve criar novos itens (úteis ou decorativos) a partir de combinações de materiais segundo receitas predefinidas, descontando-os do inventário. | Must |
| RF07 | Gerir progresso | O sistema deve gerenciar a transição entre as fases de limpeza, replantio e reconstrução do cenário conforme o avanço do jogador. | Must |
| RF08 | Desbloquear recursos | O sistema deve apresentar progressão baseada em desbloqueio de novos itens, receitas e áreas do mapa. | Must |
| RF09 | Utilizar ferramentas | O sistema deve permitir uso de ferramentas (machado, picareta, pá) com animação própria acionada por botão, independente do sprite do avatar. | Must |
| RF10 | Posicionar objetos no mapa | O sistema deve permitir ao jogador posicionar itens decorativos ou funcionais em células habilitadas do grid do mapa. | Must |
| RF11 | Sistema de plantação | O sistema deve permitir agricultura em grid: o avatar rega as plantações com ferramenta, com área de irrigação inicial de 1 célula. | Should |
| RF12 | Tela inicial | O sistema deve exibir tela inicial com as opções "Iniciar" e "Sair" (save não está no escopo do protótipo). | Must |
| RF13 | Animação do avatar | O sistema deve apresentar sprites distintos para os estados: andando, coletando (agachado) e segurando objeto acima da cabeça. | Must |

---

## Requisitos Não Funcionais

| ID | Nome | Descrição | Prioridade |
| :--- | :--- | :--- | :--- |
| RNF01 | Plataforma de implementação | O sistema deve ser desenvolvido na engine Godot, escolhida pela simplicidade de uso e suporte nativo a jogos 2D. | Must |
| RNF02 | Estética visual pixel art | Os sprites devem ser criados manualmente no Piskel, em estilo Pixel Art de baixa resolução, sem uso de geração por IA. | Must |
| RNF03 | Grid-based | O mapa deve ser dividido em células quadradas de tamanho definido, servindo de base para posicionamento de sprites e lógica de interação. | Must |
| RNF04 | Prototipagem iterativa | O protótipo deve ser entregue como demo em vídeo (produzido no After Effects e Premiere) acompanhado de uma página HTML de apresentação do projeto. | Must |
| RNF05 | Documentação versionada | Todos os artefatos (Rich Pictures, storyboards, gravações, vídeo demo, página HTML) devem ser versionados e publicados no GitHub Pages com histórico por contribuidor. | Must |
| RNF06 | Artefatos autorais | Os artefatos visuais devem ser claramente feitos por humanos; conteúdo gerado por IA será penalizado conforme critério da professora. | Must |
| RNF07 | Exportação de sprites | Os sprites e animações criados no Piskel devem ser exportados em formatos compatíveis com Godot (PNG por frame ou GIF). | Must |
| RNF08 | Validação com usuários reais | O vídeo demo deve ser apresentado a ao menos dois usuários externos com experiência no gênero para coleta de feedback antes da entrega. | Should |

---

> **Legenda:** Must = obrigatório | Should = importante | Could = desejável | Wont = fora do escopo atual

## historico de versão 

| Versão |    Data    |          Descrição          |         Autor                               |       Revisor                                      |
| :----: | :--------: | :-------------------------: | :-----------------------------------------: | :------------------------------------------------: |
|  1.0   | 12/04/2025 | Criação do documento        | [Heyttor Augusto](https://github.com/H3ytt0r62) |  |
|  1.1   | 03/04/2026 | Padronização e edição dos Requisitos seguindo FURPS+ Moscow        | [Yasmin Abdon](https://github.com/yaabdon) |  |
| 1.2   | 03/04/2026 | Revisão geral, acrescimo de requisitos e ajustes | [Carlos Henrique](https://github.com/Depaiiva) e [João Pedro](https://github.com/Jadequilin) |  |
