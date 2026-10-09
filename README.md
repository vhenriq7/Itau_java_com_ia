# Bootcamp Itaú — Java com Inteligência Artificial

Repositório para construir e versionar **projetos, desafios e atividades práticas** desenvolvidos no Bootcamp Itaú — Java com Inteligência Artificial da DIO.

## Prioridade: projetos e desafios

O objetivo principal é desenvolver **projetos reais com Java**, registrando a implementação, os testes, as decisões e a evolução no Git. Exercícios pontuais ajudam a praticar os fundamentos, mas não são o foco principal.

### 1. Projetos oficiais de Java Básico — a fazer

Os quatro projetos publicados pela DIO estão organizados em [`projetos/`](projetos/README.md):

- **01 — [Calculadora com Menu Interativo](projetos/01-calculadora-interativa/README.md)** — ainda não iniciado.
- **02 — [Jogo de Sudoku](projetos/02-jogo-sudoku/README.md)** — ainda não iniciado.
- **03 — [Jogo da Memória](projetos/03-jogo-da-memoria/README.md)** — ainda não iniciado.
- **04 — [Board de Gerenciamento de Tarefas](projetos/04-board-de-tarefas/README.md)** — ainda não iniciado.

Cada projeto tem um checklist próprio com marcos de implementação e o link ao enunciado oficial. **Nenhum projeto está marcado como concluído.**

### 2. Desafios — conforme publicação

A pasta [`desafios/`](desafios/README.md) organiza desafios independentes da trilha quando forem divulgados. No [repositório da DIO usado como fonte](https://github.com/digitalinnovationone/exercicios-java-basico) existem `projetos/` e `exercicios/`, sem diretório separado de desafios. Os **quatro projetos-desafio** estão listados na pasta `projetos/` para não duplicar implementações.

### 3. Atividades práticas — apoio aos projetos

Os **20 exercícios oficiais** estão catalogados em [`praticas/exercicios-java-basico/`](praticas/exercicios-java-basico/README.md), divididos em seis módulos. Ainda não foram resolvidos.

## Organização

```text
Itau_java_com_ia/
├── AGENTS.md
├── projetos/
│   ├── 01-calculadora-interativa/
│   ├── 02-jogo-sudoku/
│   ├── 03-jogo-da-memoria/
│   └── 04-board-de-tarefas/
├── desafios/                    # desafios independentes do bootcamp
├── praticas/
│   └── exercicios-java-basico/  # roteiro de 20 exercícios em seis módulos
└── ferramentas/
    └── dio-agent/               # DIO Agent oficial (Git submodule)
```

## DIO Agent + Codex

O [DIO Agent oficial](https://github.com/digitalinnovationone/dio-agent) é referenciado como submódulo em `ferramentas/dio-agent`. O [AGENTS.md](AGENTS.md) orienta o Codex a atuar como mentor: explicar conceitos, ajudar com diagnóstico e dar dicas graduais. **As soluções e o código dos projetos devem ser desenvolvidos pelo estudante.**

Para clonar com os submódulos:

```bash
git clone --recurse-submodules https://github.com/vhenriq7/Itau_java_com_ia.git
```

Para atualizar uma cópia local já clonada:

```bash
git pull
git submodule update --init --recursive
```

Para atualizar o DIO Agent posteriormente:

```bash
git submodule update --remote ferramentas/dio-agent
```

## Versionamento

Commits devem refletir prática real, como implementação de funcionalidades, correções, refatorações, testes ou documentação útil. Exemplos:

```text
feat: implementa menu e operações da calculadora
feat: cria validação de movimentos do sudoku
feat: adiciona persistência ao jogo da memória
feat: implementa fluxo de cards do board
fix: corrige regra de bloqueio de cards
docs: documenta execução do projeto
```

**Material dos desafios:** os enunciados são da DIO; o código produzido posteriormente será autoral. Nada foi apresentado como solução já concluída.
