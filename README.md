# estudo-ia

Meu caderno de estudos de programação com IA. A meta é entender e mexer com
segurança no código que uso no trabalho (o Money Maker, backoffice de
marketing da 12min) e automatizar tarefas do dia a dia com o Claude Code.

## Como uso este repositório

- Cada etapa do plano vira uma pasta (`01-terminal-e-git/`, `02-typescript/`...).
- Dentro dela ficam anotações, exercícios e pequenos projetos.
- Tudo entra por branch e PR, para eu praticar o fluxo de trabalho real.

## Plano de estudos

### Etapa 1: terminal e Git (semanas 1 e 2)

- [ ] Navegar no terminal: `pwd`, `ls`, `cd`, `mkdir`, `cat`
- [ ] Git no dia a dia: `status`, `add`, `commit`, `log`, `diff`
- [ ] Branches e PRs: criar branch, abrir PR, revisar e fazer merge
- [ ] GitHub CLI (`gh`) para não sair do terminal

**Entrega:** este repositório organizado, com pelo menos 5 PRs mesclados.

### Etapa 2: fundamentos de JavaScript e TypeScript (semanas 3 a 5)

- [ ] Variáveis, funções, objetos, listas e laços
- [ ] Tipos no TypeScript: por que eles evitam erros
- [ ] `async`/`await` e chamadas a APIs (`fetch`)
- [ ] Rodar scripts com Bun

**Entrega:** um script que lê um CSV de métricas de anúncios e soma gasto e
vendas por criativo.

### Etapa 3: como um sistema web funciona (semanas 6 e 7)

- [ ] O que é front-end, API e banco de dados
- [ ] HTTP na prática: rotas, métodos (GET, POST), status (200, 404, 500)
- [ ] JSON e validação de dados
- [ ] Variáveis de ambiente e por que o `.env` nunca vai para o Git

**Entrega:** uma API mínima com duas rotas, rodando local.

### Etapa 4: lendo o Money Maker (semanas 8 a 10)

- [ ] Ler `docs/PROJECT.md` e um plano em `plans/` (começar pelo 001)
- [ ] Seguir uma funcionalidade inteira: plano, tela em `apps/web`, rota em
      `apps/api`, consulta em `packages/db`
- [ ] Rodar o projeto local (`bun infra:up`, `bun dev:api`, `bun dev:web`)
- [ ] Entender a fila: o que a API faz na hora e o que vai para o worker

**Entrega:** um documento aqui explicando, com minhas palavras, como uma
funcionalidade do Money Maker funciona de ponta a ponta.

### Etapa 5: trabalhando com IA no código (semanas 11 e 12)

- [ ] Escrever bons pedidos para o Claude Code: contexto, objetivo, limite
- [ ] Ler e revisar o código que a IA gera antes de aceitar
- [ ] Rodar testes, lint e typecheck antes de cada commit
- [ ] Criar uma skill própria para uma tarefa repetitiva do marketing

**Entrega:** uma pequena melhoria no Money Maker feita por mim com ajuda da
IA, revisada e testada.

## Rotina

- 1 hora por dia útil, de preferência no mesmo horário
- Toda sexta: revisar o que foi feito e marcar os itens concluídos aqui
- Dúvida que levar mais de 30 minutos vira anotação em `duvidas.md`

## Progresso

| Etapa | Status |
| --- | --- |
| 1. Terminal e Git | em andamento |
| 2. JavaScript e TypeScript | a fazer |
| 3. Sistema web | a fazer |
| 4. Lendo o Money Maker | a fazer |
| 5. IA no código | a fazer |
