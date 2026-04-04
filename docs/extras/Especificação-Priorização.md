<!-- 
EM CONSTRUÇÃO

-->
# Especificação de Requisitos e Priorização

Este documento apresenta a consolidação dos requisitos levantados durante os 5 dias de Design Sprint. A estrutura utiliza o modelo FURPS+ para categorização técnica e a técnica MoSCoW para definição de prioridade de implementação. 

## Requisitos Funcionais

| ID | Nome | Descrição | Prioridade | Rastreabilidade |
| :--- | :--- | :--- | :--- | :-----|
| RF01 | Movimentar o avatar | O sistema deve processar entradas WASD para deslocar o avatar 2D pelo mapa. | Must | [aqui](../administracao/reunioes/20260323.md)|
| RF02 | Exibir resíduos | O sistema deve permitir a visualização de objetos coletáveis (lixo) distribuídos no mapa. | Must | [aqui](../administracao/reunioes/20260323.md)|
| RF03 | Coletar itens | O sistema deve remover o objeto do cenário e adicioná-lo ao inventário após ação/colisão do avatar. | Must | [aqui](../administracao/reunioes/20260323.md)|
| RF04 | Animar coleta (on click) | O sistema deve acionar a animação de coleta do avatar ao clicar/interagir com um item coletável. | Must | [aqui](../administracao/reunioes/20260323.md)||
| RF05 | Processar depósito/reciclagem | O sistema deve validar a proximidade à maquininha de reciclagem para processar e transformar itens do inventário. | Must | [aqui](../administracao/reunioes/20260323.md)|
| RF06 | Sistema de craft | O sistema deve criar novos itens (úteis ou decorativos) a partir de combinações de materiais segundo receitas predefinidas, descontando-os do inventário. | Must |[aqui](../administracao/reunioes/20260323.md)|
| RF07 | Gerir progresso | O sistema deve gerenciar a transição entre as fases de limpeza, replantio e reconstrução do cenário conforme o avanço do jogador. | Should|[aqui](../administracao/reunioes/20260324.md)
| RF08 | Desbloquear recursos | O sistema deve apresentar progressão baseada em desbloqueio de novos itens, receitas e áreas do mapa. | Must |[aqui](../administracao/reunioes/20260324.md)
| RF09 | Utilizar ferramentas | O sistema deve permitir uso de ferramentas (machado, picareta, pá) com animação própria acionada por botão, independente do sprite do avatar. | Must |[aqui](../administracao/reunioes/20260324.md)
| RF10 | Posicionar objetos no mapa | O sistema deve permitir ao jogador posicionar itens decorativos ou funcionais em células habilitadas do grid do mapa. | Must |[aqui](../administracao/reunioes/20260324.md)
| RF11 | Sistema de plantação | O sistema deve permitir agricultura em grid: o avatar rega as plantações com ferramenta, com área de irrigação inicial de 1 célula. | Should |[aqui](../administracao/reunioes/20260324.md)
| RF12 | Tela inicial | O sistema deve exibir tela inicial com as opções "Iniciar" e "Sair" (save não está no escopo do protótipo). | Must |[aqui](../administracao/reunioes/20260324.md)
| RF13 | Animação do avatar | O sistema deve apresentar sprites distintos para os estados: andando, coletando (agachado) e segurando objeto acima da cabeça. | Must |[aqui](../administracao/reunioes/20260326.md)
| RF14 | Música por cenário | O sistema deve suportar trilha ou efeitos sonoros por cenário para aumentar a imersão do protótipo. | Could |[aqui](../administracao/reunioes/20260326.md)
| RF15 | Construções simples | O sistema deve permitir construções simples como casa ou moinho. | Should |[aqui](../../administracao/reunioes/20260326.md)
| RF16 | Sistema de combate | O sistema de combate deve ser considerado apenas como incremento de escopo futuro, em baixa prioridade. | Could | [aqui](../administracao/reunioes/20260326.md)
| RF17 | Múltiplos mapas | O sistema deve suportar múltiplos mapas apenas como expansão de escopo, em baixa prioridade. | Could |[aqui](../administracao/reunioes/20260326.md)
| RF18 | Missões complexas | O sistema deve incluir missões complexas apenas como incremento de escopo futuro. | Could |[aqui](../administracao/reunioes/20260326.md)
| RF19 | Sistema de mercado/guilda | O sistema deve incluir mercado ou guilda apenas como funcionalidade extra de baixa prioridade. | Could |[aqui](../administracao/reunioes/20260326.md)|
|RF20| Tamanho do inventario | Inventário deve conter 8 espaços na barra fixa e 16 na mochila, totalizando 24 espaços. | Must | [aqui](../administracao/reunioes/20260327.md)|
|RF21| Acumulho de  itens no inventario| Cada item pode acumular até 12 unidades por espaço. | Must| [aqui](../administracao/reunioes/20260327.md)|
|RF22| quantidade de itens |A quantidade de cada item deve ser exibida dentro do quadrado correspondente no inventário.| Must| [aqui](../administracao/reunioes/20260327.md)|
|RF23| Loja | O sistema deve possuir um sistema de compra e venda de itens disponivel | Must | [Aqui](../administracao/reunioes/20260326.md)|
|RF24| Compra e venda | O sistema de loja deve aceitar a compra de materias adquiridos durante o gameplay do jogo e oferecer sementes para o plantio | Must | [aqui](../administracao/reunioes/20260326.md) |
|RF25| Agricultura| As sementes so podem ser plantadas em terreno arado | Should |  [aqui](../administracao/reunioes/20260326.md) |
|RF26| Reguador | Se uma semente não for regada, seu cressimento (mudança de sprite) não acontece | Should | [aqui](../administracao/reunioes/20260326.md) |
| RF27| Cresimento | Caso seja molhada todos so dias, a planta em 4 ciclos chegara em sua forma final| Should| [aqui](../administracao/reunioes/20260326.md) |
|RF28 | Sono | Quando o protagonista entrar em sua casa um dia se passa, fazendo plantas cresserem e mais lixo aparecer| Could| [aqui](../administracao/reunioes/20260326.md) | 
|RF29| Venda| O jogador pode vender suas plantas cultivadas e lixos para a loja conseguindo dinheiro | Must| [aqui](../administracao/reunioes/20260326.md) |
|RF30| Dinheiro| Ao vender itens o jogador ganha certa quantia de dinheiro que pode ser usado na propia loja | Must| [aqui](../administracao/reunioes/20260326.md) |


---

## Requisitos Não Funcionais

| ID | Nome | Descrição | Prioridade | Rastreabilidade |
| :--- | :--- | :--- | :--- | :------|  
| RNF01 | Plataforma de implementação | O sistema deve ser desenvolvido na engine Godot, escolhida pela simplicidade de uso e suporte nativo a jogos 2D. | Must |[aqui](../administracao/reunioes/20260326.md)|
| RNF02 | Estética visual pixel art | Os sprites devem ser criados manualmente no Piskel, em estilo Pixel Art de baixa resolução, sem uso de geração por IA. | Must |[aqui](../administracao/reunioes/20260326.md)|
| RNF03 | Grid-based | O mapa deve ser dividido em células quadradas de tamanho definido, servindo de base para posicionamento de sprites e lógica de interação. | Must |[aqui](../administracao/reunioes/20260326.md)|
| RNF04 | Prototipagem iterativa | O protótipo deve ser entregue como demo em vídeo (produzido no After Effects e Premiere) acompanhado de uma página HTML de apresentação do projeto. | Must |[aqui](../administracao/reunioes/20260326.md)|
| RNF05 | Documentação versionada | Todos os artefatos (Rich Pictures, storyboards, gravações, vídeo demo, página HTML) devem ser versionados e publicados no GitHub Pages com histórico por contribuidor. | Must |[aqui](../administracao/reunioes/20260326.md)|
| RNF06 | Artefatos autorais | Os artefatos visuais devem ser claramente feitos por humanos; conteúdo gerado por IA será penalizado conforme critério da professora. | Must |[aqui](../administracao/reunioes/20260326.md)|
| RNF07 | Exportação de sprites | Os sprites e animações criados no Piskel devem ser exportados em formatos compatíveis com Godot (PNG por frame ou GIF). | Must |[aqui](../administracao/reunioes/20260326.md)|
| RNF08 | Validação com usuários reais | O vídeo demo deve ser apresentado a ao menos dois usuários externos com experiência no gênero para coleta de feedback antes da entrega. | Should |[aqui](../administracao/reunioes/20260326.md)|
|RNF09 | Garantir a integridade dos dados no GitPages.| Todo o histórico de versões e documentação deve ser mantido de forma íntegra no repositório do grupo. | Must| [aqui](../administracao/reunioes/20260323.md)|
|RNF10| Tamanho dos blocos | Cada bloco do cenário deve ter um tamanho T, em pixels. | Must | [aqui](../administracao/reunioes/20260327.md)|
|RNF11| Tamanho do jogador| O jogador deve ter tamanho equivalente a 2T pixels. | Must| [aqui](../administracao/reunioes/20260327.md)|
|RNF12| Tamanho das ferramentas | Ferramentas devem ter tamanho aproximado de 1,5T pixels.| Must| [aqui](../administracao/reunioes/20260327.md)|
|RNF13| tamanho do mundo | O mundo deve ser pelo menos 1000x maior que o jogador| Must | [aqui](../administracao/reunioes/20260327.md)|





---

> **Legenda:** Must = obrigatório | Should = importante | Could = desejável | Wont = fora do escopo atual

## historico de versão 

| Versão |    Data    |          Descrição          |         Autor                               |       Revisor                                      |
| :----: | :--------: | :-------------------------: | :-----------------------------------------: | :------------------------------------------------: |
|  1.0   | 12/04/2025 | Criação do documento        | [Heyttor Augusto](https://github.com/H3ytt0r62) |  |
|  1.1   | 03/04/2026 | Padronização e edição dos Requisitos seguindo FURPS+ Moscow        | [Yasmin Abdon](https://github.com/yaabdon) |  |
| 1.2   | 03/04/2026 | Revisão geral, acrescimo de requisitos e ajustes | [Carlos Henrique](https://github.com/Depaiiva) e [João Pedro](https://github.com/Jadequilin) |  |
| 1.3 | 04/04/2025 | Adição de rastreabilidade e mudança do local do arquico | [Heyttor augusto](https://github.com/H3ytt0r62) | |
