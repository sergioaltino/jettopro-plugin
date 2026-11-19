---
name: jettopro
description: Trabalhar nos projetos do JettoPro pelo conector. Use quando a pessoa falar dos projetos, tarefas, prazos, riscos, mudanças, horas, lições ou da base de conhecimento dela no JettoPro, ou pedir para criar ou atualizar algo lá.
---

# Como trabalhar com o JettoPro

O conector JettoPro age com as permissões de quem conectou. Ele não apaga nada.

## Antes de criar ou mudar algo

1. Descubra o projeto. Se a pessoa não disse qual é, use `listar_projetos` e pergunte. Cite o código, por exemplo OBRA1.
2. Para criar um projeto com `criar_projeto_completo`, a pessoa precisa dizer o método (preditivo, híbrido, Scrum ou
   Kanban) e a data de início. Se ela não disse, pergunte. Sugira um código curto e confirme com ela.
3. Para criar um item, use só o que a pessoa disse. Não invente prazo, responsável nem descrição. Depois de criar, conte o
   que ficou de fora.
4. Mostre o que vai fazer e espere a confirmação antes de gravar.

## Mudanças no plano

- Prazo, duração, responsável, itens que entram ou saem do escopo, ligações e orçamento passam por `solicitar_mudanca`.
  Ela só monta a solicitação, e nada muda nos itens até alguém aprovar.
- Aprovar é só no app, por quem aprova mudanças no projeto. Não tente aprovar com `mudar_estado`.

## Respostas

- Cite o link de cada registro que aparecer na resposta.
- Datas no formato dd/mm/aaaa e valores em reais.
- Quando uma ferramenta recusar por permissão ou por plano, diga isso com as palavras dela e não tente outro caminho.
