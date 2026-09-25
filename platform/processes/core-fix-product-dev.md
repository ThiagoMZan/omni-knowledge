# Correção no Core — abrir item para Produto aplicar na build master

## Quando usar

Quando uma correção é feita no **core**, é necessário abrir um item para o time de **Produto** para que a alteração seja aplicada na **build master**.

Este registro existe principalmente como lembrete do fluxo interno para criar essa solicitação.

## Forma recomendada: criar a partir do card relacionado

No card que originou a correção:

1. Vá até a seção **Itens vinculados**.
2. Clique em **Novo**.
3. No campo **Processo**, selecione **Produto-Dev**.
4. Preencha os dados da solicitação.

### Campos principais

- **Processo:** Produto-Dev
- **Tipo de tarefa:** Problema
- **Produto:** OMNI
- **Time de produto:** OMNI
- **Release:** selecionar quando aplicável
- **Título:** descrever objetivamente a correção que precisa entrar na master
- **Cliente:** selecionar o cliente relacionado ao card/origem
- **Squad:** selecionar a squad responsável
- **Responsável:** preencher quando aplicável
- **Horas de desenvolvimento:** preencher quando aplicável
- **Tamanho:** preencher quando aplicável
- **Descrição:** explicar a correção feita no core e o que Produto precisa levar para a build master
- **Data de início / Data de fim:** preencher conforme o planejamento
- **P&D:** selecionar quando aplicável
- **Card com impedimento:** marcar quando aplicável
- **Análise conclusiva:** preencher quando aplicável

### Exemplo visual observado

Na tela de criação, o exemplo utilizado estava com:

- Processo: `Produto-Dev`
- Tipo de tarefa: `Problema`
- Produto: `OMNI`
- Time de produto: `OMNI`
- Cliente: `UOL`
- Squad: `Júpiter`

Esses últimos campos são exemplos e devem ser ajustados conforme o caso.

## Alternativa: abrir diretamente pelo menu de Processos

Também é possível criar o item pelo menu:

**Processos → Produto-Dev**

A diferença importante é que, criado dessa forma, **o novo item não fica automaticamente vinculado ao card que originou a correção**.

Por isso, quando existe um card relacionado, prefira criar por:

**Card → Itens vinculados → Novo → Produto-Dev**

## Objetivo final

O item de Produto-Dev deve deixar claro que existe uma **correção realizada no core** que precisa ser incorporada pelo time de Produto à **build master**.

## Tags

`core` `produto-dev` `build-master` `processo-interno` `workflow` `omni`
