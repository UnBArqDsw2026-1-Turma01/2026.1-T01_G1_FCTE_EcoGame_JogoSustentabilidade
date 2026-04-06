# BPMN 

## Introdução
<p align="justify">
A Notação de Gerenciamento de Processos de Negócio (BPMN) é um padrão internacional voltado para a diagramação de fluxos de trabalho. Adotada pela Object Management Group (OMG), essa notação permite a representação visual de processos de forma padronizada, facilitando a comunicação entre técnicos e gestores de negócio.
</p>

<p align="justify">
No contexto deste projeto, a modelagem BPMN foi utilizada para mapear os processos internos do <b>EcoGame</b>, como os fluxos de reciclagem, plantio e gestão de inventário, garantindo que a lógica de funcionamento do software esteja alinhada aos requisitos elicitados.
</p>

## Elementos de Modelagem Utilizados
De acordo com a metodologia apresentada pela (<a href="#ref-bpmn">Professora Milene Serrano</a>), utilizamos as seguintes abstrações para compor os diagramas:

- Piscinas (Pools): Containeres que representam os participantes principais do processo.

- Raias (Lanes): Sub-partições utilizadas para organizar atividades por papéis ou sistemas específicos.

- Atividades: Pontos onde o trabalho é realizado, descritos com verbos no infinitivo ou na terceira pessoa do singular.

- Gateways: Elementos de decisão que controlam a divergência ou convergência do fluxo (Exclusivos, Inclusivos ou Paralelos).

- Conectores: Elementos que mostram a ordem de sequenciamento das atividades e mensagens.

## Colaboração Remota
A equipe realizou uma reunião remota integrada para consolidar o planejamento do projeto. O trabalho iniciou-se com a criação de um documento editável no Google Docs, servindo como base textual para as decisões do grupo.
Para alinhar os processos, houve uma discussão intensa de uma hora envolvendo todos os integrantes, utilizando simultaneamente o Google Meet para a conferência de voz/vídeo e o WhatsApp para a troca rápida de informações e registros.

Destaques da produção:

- Modelagem Inicial: Com base no que foi acordado coletivamente, o integrante Gabriel desenvolveu a primeira versão do diagrama BPMN utilizando o draw.io (configurado para sincronização em tempo real).

- Ciclo de Revisão: Após a publicação dessa versão inicial, os demais integrantes realizaram rodadas de revisão, gerando versões subsequentes que refinaram o fluxo e garantiram a precisão técnica do mapeamento.


## Registro Visual: Modelagem do Processo
| Versão do Artefato | Data | Colaboradores | Registro Visual |
| :---: | :---: | :--- | :--- | 
| **V1** | 04/03/2026 | Gabriel | [aqui](../../../assets/images/Edicao_Gabriel.png) |
| **V2** | 04/03/2026 | Yasmin  | [aqui](../../../assets/images/Edicao_Yasmin.drawio.png) |
| **V3** | 04/03/2026 | Ryan | [aqui](../../../assets/images/Edicao_Ryan.drawio.png) |
| **V4** | 05/03/2026 | Heyttor | [aqui](../../../assets/images/Edicao_Heyttor.drawio.png) |
| **V5 (Final)** | 05/04/2026 | Equipe | [aqui](../../../assets/images/Edicao_Heyttor.drawio.png) |


## Conclusão
<p align="justify">
A modelagem BPMN serve como a ponte entre o <b>Brainstorming</b> (ideação) e a <b>Especificação de Requisitos</b>. Cada atividade mapeada nos diagramas acima possui rastreabilidade direta com os Requisitos Funcionais (RFs) definidos no projeto, assegurando que o desenvolvimento na engine Godot siga um fluxo lógico validado.
</p>

## Bibliografia

  > <a id="ref-bpmn"></a>SERRANO, Milene. Arquitetura e Desenho de Software: Aula BPMN Exemplos. Brasília: UnB Gama, [2019]. Disponível em: Moodle/Aprender UnB. Acesso em: 5 abr. 2026.


## Histórico de versão

| Versão |    Data    |          Descrição          |         Autor                               |       Revisor                                      |
| :----: | :--------: | :-------------------------: | :-----------------------------------------: | :------------------------------------------------: |
|  1.0   | 05/04/2026 | Preenchimento da página e inserção das versões editadas do BPMN | [Yasmin Abdon](https://github.com/yaabdon) | |


