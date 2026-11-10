# Semana 01: Git e GitHub

Criação do repositório da capacitação, com currículo, painel das semanas e prática de branches, Pull Requests e conflito de merge.

## O que foi feito

- `.gitignore` e uma pasta para cada semana
- Currículo no README principal (PR #1)
- Painel das semanas com a coluna **"Na prática"**, minha visão única (PR #2)
- Conflito de merge provocado e resolvido
- Commits no padrão Conventional Commits

## Como rodar

Não há nada para executar nesta semana. O resultado está no próprio repositório: README principal, branches, Pull Requests e histórico de commits.

## Commits

| Tipo | Exemplo do meu histórico |
|---|---|
| `chore` | `chore: adiciona .gitignore` |
| `docs` | `docs: adiciona painel da capacitação com coluna específica 'Na prática'` |
| `fix` | `fix: resolve conflito de merge entre títulos do README` |

[Ver todos os commits](https://github.com/felipesouzx/capacitacao-asimov-felipe-souza/commits/semana-01-git)

## Conflito de merge

A primeira linha do README mudou em duas branches: na `semana-01-git` ela virou "Capacitação Asimov Jr | Felipe Augusto", e na `main` virou "Felipe Augusto". Ao rodar `git merge main`, o Git não tinha como decidir qual versão manter. Resolvi no VS Code, mantive "Felipe Augusto" porque o README virou meu currículo e concluí o merge com um commit `fix:`.

## Dificuldades

- Começar a usar o padrão Conventional Commits e a nova forma de organizar os commits, pensando no tipo e na descrição de cada mudança.
- Organizar o fluxo de branches para provocar o conflito de merge de propósito, sem bagunçar a `main`.
- Esqueci de fazer um commit antes de abrir o PR #2. Descobri que um novo push para a mesma branch atualiza o PR aberto.