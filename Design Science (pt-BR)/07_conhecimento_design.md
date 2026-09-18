---
title: "De Artefato a Conhecimento de Design"
description: "Como extrair e articular conhecimento transferível a partir de pesquisa DSR"
author: "Carlos Quintella"
date: 2026-09-18
tags: [DSR, conhecimento, design-principles, contribuicao]
---

# Capítulo 7: De Artefato a Conhecimento de Design

## O Ponto Culminante

O valor científico de uma pesquisa DSR não está no artefato específico. Está no **conhecimento de design** que você articula.

Um artefato é específico de um contexto. Conhecimento de design é **transferível**.

## Formas de Conhecimento de Design

### Design Principles

Diretrizes sobre como construir artefatos similares em contextos similares.

**Estrutura de um design principle bem articulado:**
- **Quando aplicável:** Em quais contextos? Que características?
- **Por que funciona:** Qual a fundamentação teórica?
- **Que trade-offs:** Benefício vs. custo?
- **Limitações:** Em que condições falha?

**Exemplo:**

"Em sistemas de detecção de anomalias onde padrões normais evoluem temporalmente, incorporar mecanismos de **retraining periódico** + **feedback contínuo de especialistas** reduz significativamente false positives ao longo do tempo.

*Por quê:* Modelos fixos degradam com concept drift; feedback humano identifica novas formas de anomalia.

*Trade-off:* Retraining tem custo computacional; requer expertise disponível continuamente.

*Aplica-se a:* Segurança, detecção de fraude, monitoramento de saúde (qualquer contexto de evoluções dinâmicas)."

### Design Patterns

Soluções recorrentes para problemas específicos. Mais específicos que principles. Documentam:
- Nome e descrição breve
- Quando aplicável
- Como implementar
- Trade-offs e limitações

### Taxonomies

Organizam espaço de soluções. Exemplo: "Tipologia de estratégias de cache em edge computing" — articula dimensões, opções, trade-offs.

### Process Knowledge

Como executar uma classe de tarefas. Exemplo: "Processo para migração de monolito para microsserviços baseado em 5 contextos diferentes."

### Insights Teóricos

Entendimentos sobre por que designs funcionam. Exemplo: "Em sistemas críticos, descentralização reduz latência mas aumenta complexidade operacional — há trade-off fundamental entre performance e inteligibilidade."

## De Específico a Generalizado

A passagem de "neste contexto funcionou" para "estes principles funcionam" exige reflexão sistemática:

1. **O que fez diferença?** Que elementos do design produziram o resultado observado?
2. **Em que contextos é aplicável?** Quais características contextuais importam?
3. **Por que funcionou?** Qual é a lógica subjacente (teoria)?
4. **Qual o alcance?** Outros contextos similares? Dissimilares?

## Matriz de Gregor & Hevner

Como posicionar sua contribuição:

```
                Compreensão do Problema
                Baixa ←→ Alta
Solução        ┌─────────┬─────────┐
Exploratória   │ Exploratory Design  │
               │ (novo problema,     │
               │  nova solução)      │
Incremental    │ Improvement Design  │
               │ (problema conhecido,│
               │  solução melhor)    │
               └─────────┴─────────┘
```

Uma pesquisa que aborda problema bem compreendido com solução incremental foca em **rigor e eficiência**. Uma que aborda problema pouco compreendido com solução radical foca em **geração de novo conhecimento**.

---

## Conexões com Outros Capítulos

- **Capítulo 3** introduz tipos de conhecimento
- **Capítulo 8** mostra como contemporaneamente (2024+) DSR está evoluindo

---

## Resumo

| Forma | Descrição | Aplicação |
|-------|-----------|-----------|
| **Principle** | Diretriz generalizável | Guiar futuros designs |
| **Pattern** | Solução recorrente | Reconhecer problema similar |
| **Taxonomy** | Organização do espaço | Compreender opções |
| **Process** | Como executar | Replicabilidade |
| **Insight** | Entendimento teórico | Fundamentação |

---

**Anterior:** [Capítulo 6: Avaliação](06_avaliacao.md)  
**Próximo:** [Capítulo 8: DSR Contemporânea →](08_dsr_contemporanea.md)
