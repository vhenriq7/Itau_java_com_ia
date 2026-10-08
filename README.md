# Bootcamp Itaú — Java com Inteligência Artificial

Repositório prático para registrar códigos, desafios e projetos desenvolvidos durante o Bootcamp Itaú — Java com Inteligência Artificial na DIO.

## Objetivo

Este repositório não é um diário de aulas. O foco é versionar **o que foi feito na prática**: exercícios executáveis, desafios resolvidos e projetos desenvolvidos durante a trilha.

## Estrutura

```text
Itau_java_com_ia/
├── AGENTS.md
├── ferramentas/
│   └── dio-agent/        # DIO Agent oficial, como submodule
├── praticas/             # Exercícios e experimentos práticos
├── desafios/             # Desafios de código/projeto
└── projetos/             # Projetos maiores do bootcamp
```

## DIO Agent + Codex

O repositório oficial [digitalinnovationone/dio-agent](https://github.com/digitalinnovationone/dio-agent) está conectado em `ferramentas/dio-agent` como **Git submodule**. Assim, o material da DIO continua identificado como dependência externa e pode ser atualizado sem misturar autoria com os códigos deste repositório.

O `AGENTS.md` da raiz orienta o Codex a usar o DIO Agent como referência de mentoria, especialmente as skills de:

- explicar conceitos;
- destravar desafios com dicas graduais;
- plano de estudos;
- pesquisa na web quando necessário.

### Ao clonar este repositório

Use:

```bash
git clone --recurse-submodules https://github.com/vhenriq7/Itau_java_com_ia.git
```

Se você já clonou o repositório antes de o submodule ser adicionado:

```bash
git pull
git submodule update --init --recursive
```

### Atualizar o DIO Agent depois

```bash
git submodule update --remote ferramentas/dio-agent
```

## Regra de versionamento

Commits devem representar prática real. Exemplos:

```text
feat: adiciona exercício de estruturas condicionais
feat: implementa desafio de orientação a objetos
refactor: reorganiza classes do exercício de herança
fix: corrige validação do desafio de entrada de dados
docs: documenta execução do projeto final
```

O objetivo é que o histórico mostre evolução técnica real, e não atividade artificial no GitHub.
