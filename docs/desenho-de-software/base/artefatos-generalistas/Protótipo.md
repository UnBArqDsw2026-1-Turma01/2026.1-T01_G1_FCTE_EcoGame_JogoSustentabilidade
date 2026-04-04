<!--Written by l0c, v1.0-->
<!--this is a model! copy this into the actual files and stuff-->
<!--Remember -> mkdocs may break in unexpected ways. Always check your links!-->

# Documentação do Protótipo: Sistema de Interação e Inventário

## 1. Visão Geral

Este protótipo consiste em um sistema interativo desenvolvido para um jogo ou simulação, focado na **coleta de itens** (lixo), **gerenciamento de inventário** e **interação com o cenário** (plantas e máquinas). O projeto destaca-se pela organização modular de ativos e colaboração entre múltiplos desenvolvedores e designers.

---

## 2. Divisão de Responsabilidades

A equipe dividiu a criação dos componentes da seguinte forma:

| Membro | Responsabilidades |
| :----: | :-------------- |
| **Heyttor** | Desenvolvimento e comportamento do Protagonista (boneco) |
| **Yasmin** | Criação e assets das Plantas (árvores) e do sistema/objetos de Lixo |
| **Jose** | Design e implementação da Tela de Início do sistema |
| **João** | Desenvolvimento das Ferramentas, sistema de Inventário, modelo/interação da Casinha e organização/edição do video|

---

## 3. Arquitetura de Pastas e Ativos

O projeto segue uma organização lógica para facilitar a integração:

| Pasta | Conteúdo | Responsável |
| :--: | :---- | :----: |
| `/protagonista` | Sprites, scripts de movimento e animações do personagem | Heyttor |
| `/maquina` | Assets da "casinha" ou máquinas de processamento | João |
| `/lixo` | Modelos de resíduos a serem coletados no cenário | Yasmin |
| `/inventario` | Interface de usuário (UI) e lógica de armazenamento de itens | João |
| `/gifs` | Registros visuais das funcionalidades e animações | João |
| `/ferramenta` | Itens utilizáveis pelo protagonista (pás, regadores, etc.) | João |
| `/árvore_plantas` | Elementos de cenário e vegetação interativa | Yasmin |

---

## 4. Análise de Funcionalidades

### 4.1 Movimentação e Personagem
O protagonista possui controles de movimentação fluida pelo cenário, permitindo a exploração das diferentes zonas de interesse.

### 4.2 Coleta e Lixo
O sistema identifica objetos classificados como "lixo" espalhados pelo mapa. Ao interagir com eles, o item é removido do cenário e enviado para o buffer do jogador.

### 4.3 Sistema de Inventário
O inventário é uma peça central da interface, exibindo de forma visual os itens coletados:

- **Slots**: Espaços definidos para cada tipo de recurso
- **Feedback Visual**: Ícones representativos que facilitam a identificação rápida pelo usuário

### 4.4 Interação com o Cenário
- **Vegetação**: As plantas e árvores compõem o ecossistema, servindo como pontos de referência ou objetivos de cuidado
- **Processamento**: A "casinha" ou máquina funciona como o ponto de entrega ou transformação dos itens coletados

---

## 5. Fluxo do Protótipo

```
┌─────────────────────────────────────────┐
│ 1. Início                               │
│    Tela inicial (Jose)                  │
└────────────────┬────────────────────────┘
                 ↓
┌─────────────────────────────────────────┐
│ 2. Exploração                           │
│    Controle do boneco (Heyttor)        │
└────────────────┬────────────────────────┘
                 ↓
┌─────────────────────────────────────────┐
│ 3. Coleta                               │
│    Identificação de lixo (Yasmin)      │
│    Uso de ferramentas (João)           │
└────────────────┬────────────────────────┘
                 ↓
┌─────────────────────────────────────────┐
│ 4. Gestão                               │
│    Inventário organiza coleta (João)    │
└────────────────┬────────────────────────┘
                 ↓
┌─────────────────────────────────────────┐
│ 5. Finalização                          │
│    Interação com máquina/casa           │
│    Conclusão do ciclo                   │
└─────────────────────────────────────────┘
```

---

## 6. Links de Referência

- 📹 [Vídeo Demonstrativo](https://www.youtube.com/watch?v=xUc6wOs1BFg)
- 📁 [Repositório de Arquivos](https://drive.google.com)

## Histórico de versão

| Versão |    Data    |          Descrição           |                      Autor                       | Revisor |
| :----: | :--------: | :--------------------------: | :----------------------------------------------: | :-----: |
|  1.0   | 03/04/2026 | Criação da documentação do protótipo | [Daniel Nunes Daurte](https://github.com/DanNunes777) |         |