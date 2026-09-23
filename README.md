# OMNI Knowledge

Base de conhecimento técnica para registrar incidentes, bugs, troubleshooting, decisões de arquitetura, integrações e padrões reutilizáveis.

## Objetivo

Centralizar conhecimento técnico que normalmente fica espalhado em conversas, tickets, commits e memória individual. A base deve ajudar em três momentos:

1. Diagnosticar problemas novos comparando com casos anteriores.
2. Registrar soluções de bugs e incidentes de forma reutilizável.
3. Preservar decisões técnicas, padrões e particularidades da plataforma.

## Estrutura

- `bugs/` — bugs resolvidos com sintomas, causa e solução.
- `troubleshooting/` — procedimentos de diagnóstico e investigação.
- `architecture/` — decisões e explicações arquiteturais.
- `integrations/` — APIs, mensageria, WhatsApp, serviços externos etc.
- `database/` — PostgreSQL, SQL Server, queries, locks, índices e afins.
- `frontend/` — Vue, HTML, CSS, componentes e comportamento de UI.
- `backend/` — Nashorn, Java, serviços, APIs, jobs e regras de negócio.
- `platform/` — particularidades da plataforma, Studio, low-code e runtime.
- `patterns/` — soluções e padrões técnicos reutilizáveis.
- `templates/` — modelos usados para novos registros.

## Como registrar conhecimento

Use linguagem natural e preserve o contexto necessário para entender o problema no futuro.

Para bugs e incidentes, prefira registrar:

- contexto;
- sintomas;
- evidências;
- investigação;
- causa raiz, quando conhecida;
- solução aplicada;
- validação;
- prevenção ou observações;
- tags.

Nem todo bug precisa entrar na base. Priorize casos com chance de recorrência, diagnóstico não óbvio, particularidades da plataforma ou aprendizado reutilizável.

## Convenção de nomes

Use nomes descritivos em kebab-case.

Exemplo:

```text
bugs/2026-09-15-database-unavailable.md
integrations/whatsapp-template-header-image.md
database/postgres-lock-diagnosis.md
```

Para incidentes pontuais, prefixe a data quando ela ajudar a contextualizar o registro.

## Uso com IA

Antes de investigar um problema novo, a IA pode pesquisar nesta base por incidentes, padrões ou sintomas semelhantes.

Ao concluir uma investigação, o conteúdo da conversa pode ser consolidado em um novo registro, removendo tentativas irrelevantes e preservando apenas o conhecimento útil.

## Princípio

A fonte oficial é este repositório. ChatGPT, Codex e outras ferramentas são interfaces para consultar e alimentar a mesma base de conhecimento.
