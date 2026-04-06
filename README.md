# G1 - JogoSustentabilidade

Documentação do projeto G1_JogoSustentabilidade da disciplina de Arquitetura e Desenho de Software - FCTE/UnB, 2026.1.

## Membros do grupo
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Depaiiva">
        <img style="border-radius: 50%;" src="https://github.com/Depaiiva.png" width="150px;" alt=""/>
        <br /><sub><b>Carlos Henrique de Paiva Munis</b></sub></a><br />
    </td>
    <td align="center">
      <a href="https://github.com/gbevi">
        <img style="border-radius: 50%;" src="https://github.com/gbevi.png" width="150px;" alt=""/><br /><sub><b>Gabriel Dantas Bevilaqua Mendes</b></sub></a><br />
    </td>
    <td align="center">
      <a href="https://github.com/guilhermezan42">
        <img style="border-radius: 50%;" src="https://github.com/guilhermezan42.png" width="150px;" alt=""/><br /><sub><b>Guilherme Costa Zanella</b></sub></a><br />
    </td>
      </tr>
      <tr>
    <td align="center">
      <a href="https://github.com/H3ytt0r62">
        <img style="border-radius: 50%;" src="https://github.com/H3ytt0r62.png" width="150px;" alt=""/>
        <br /><sub><b>Heyttor Augusto de Assis Silva</b></sub></a><br />
    </td>
    <td align="center">
      <a href="https://github.com/Jadequilin">
        <img style="border-radius: 50%;" src="https://github.com/Jadequilin.png" width="150px;" alt=""/>
        <br /><sub><b>João Pedro Araújo de Freitas Lyra</b></sub></a><br />
    </td>
    <td align="center">
      <a href="https://github.com/Jose1277">
        <img style="border-radius: 50%;" src="https://github.com/Jose1277.png" width="150px;" alt=""/>
        <br /><sub><b>José Oliveira</b></sub></a><br />
    </td>
    <td align="center">
      <a href="https://github.com/MatheusHenrickSantos">
        <img style="border-radius: 50%;" src="https://github.com/MatheusHenrickSantos.png" width="150px;" alt=""/>
        <br /><sub><b>Matheus Henrick</b></sub></a><br />
    </td>
    <td align="center">
      <a href="https://github.com/yaabdon">
        <img style="border-radius: 60%;" src="https://github.com/yaabdon.png" width="150px;" alt=""/>
        <br /><sub><b>Yasmin Sousa Abdon</b></sub></a><br />
    </td>
  </tr>
</table>

## Pré-requisitos

- [Python 3](https://www.python.org/downloads/) (3.9 ou superior)
- [pip](https://pip.pypa.io/en/stable/installation/)
- [Git](https://git-scm.com/)

## Como rodar localmente

1. Clone o repositório:

```bash
git clone https://github.com/UnBArqDsw2026-1-Turma01/grupo-1.git
cd grupo-1
```

2. Crie e ative o ambiente virtual:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

> No Windows, use: `.venv\Scripts\activate`

3. Instale as dependências:

```bash
pip install mkdocs-material
```

4. Rode o servidor local:

```bash
mkdocs serve
```

5. Acesse no navegador: [http://127.0.0.1:8000](http://127.0.0.1:8000)

As alterações nos arquivos `.md` são atualizadas automaticamente.

## Deploy (GitHub Pages)

1. Certifique-se de estar com o ambiente virtual ativado:

```bash
source .venv/bin/activate
```

2. Execute o deploy:

```bash
mkdocs gh-deploy --force
```

3. Na primeira vez, ative o GitHub Pages no repositório:
   - Acesse **Settings** > **Pages**
   - Em **Source**, selecione a branch `gh-pages` e pasta `/ (root)`
   - Clique em **Save**

O site ficará disponível em: https://unbArqdsw2026-1-turma01.github.io/grupo-1/

## Estrutura do projeto

```
grupo-1/
├── mkdocs.yml          # Configuração do MkDocs
├── docs/
│   ├── index.md        # Página inicial
│   ├── custom.css      # Estilos customizados
│   ├── dinamica-1/     # Artefatos da Dinâmica I
│   ├── dinamica-2/     # Artefatos da Dinâmica II
│   ├── dinamica-3/     # Artefatos da Dinâmica III
│   ├── dinamica-4/     # Artefatos da Dinâmica IV
│   └── extras/         # Documentos extras
└── .venv/              # Ambiente virtual (não commitado)
```
