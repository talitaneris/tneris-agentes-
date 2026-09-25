# Agentes ativos (atualizado em 25/09/2026)

Só estes agentes estão ligados. Nenhum agente, humano ou ferramenta (Claude, Hermes) deve instalar ou chamar um agente que não esteja nesta lista.

| Agente | Função | Onde roda | Arquivo |
|---|---|---|---|
| **Alex** | Diretor Visual: carrossel, capa de Reels, arte de evento, apresentação, guia | Claude | `alex.md` |
| **People** | Estrategista de Conteúdo: pauta, roteiro, legenda, calendário | Claude | `people-SKILL-v2.md` |
| **Mariah** | Agente executiva e generalista: faz absolutamente tudo (agenda, inbox, prioridades, conteúdo, arte, qualquer tarefa). Para arte segue a skill do Alex; para conteúdo segue a skill da People | Hermes | `tneris-contexto-privado/05-squad/mariah-agente-executiva.md` |

## Fluxo

```
Talita → People (roteiro) → Alex (arte) → Talita aprova        (no Claude)
Talita ↔ Mariah (qualquer tarefa, inclusive arte e conteúdo)      (no Hermes)

Quando a Mariah fizer arte ou conteúdo, ela usa as mesmas regras do Alex e da People.
As skills são a fonte única: o que for aprovado vale para os três.
```

## Pausados

Fonte oficial das skills ativas: `talitaneris/squad-tneris-skills`. Este repositório guarda cópias.

Guardados em `pausados/` para religar quando a Talita pedir. Não apagar.

- Agentes: Paulo, Vega, Lua, Marta, Jay, Sofia, Mari, Lia, Lens, Assistente e a People v1 (`people.md`)
- Skills avulsas: carrossel-instagram, hooks-magneticos, cortes-de-video, roteiro-pauta-quente, link-in-bio, analise-instagram, dashboard-metricas, relatorio-metricas, instagram-analyzer, avoid-ai-writing

Para religar um agente: mover a pasta ou o arquivo de volta de `pausados/`, revisar se as regras dele ainda batem com o padrão atual e atualizar esta lista.
