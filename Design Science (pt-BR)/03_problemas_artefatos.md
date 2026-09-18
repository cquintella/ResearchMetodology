---
title: "Problemas, Artefatos e Contribuições em DSR"
description: "Como identificar problemas científicos válidos, tipos de artefatos, e extrair conhecimento generalizável"
author: "Carlos Quintella"
date: 2026-09-18
tags: [DSR, problema, artefato, conhecimento-design]
---

# Capítulo 3: Problemas, Artefatos e Contribuições

## O Conceito de Problema em Design Science Research

Um problema em DSR não é simplesmente qualquer situação incômoda ou qualquer necessidade não-atendida. Um problema em DSR é **uma lacuna entre um estado desejado e um estado atual, onde essa lacuna é relevante tanto para a prática quanto para o conhecimento científico**.

Essa dualidade é crucial. O problema deve ser relevante para **alguém no mundo real** — uma organização que enfrenta um desafio, um grupo de usuários que tem uma necessidade, um contexto onde algo não funciona bem. Mas também deve ser relevante para **a pesquisa** — deve revelar uma oportunidade de produzir conhecimento que não existe ou que está incompleto na literatura.

Frequentemente, os dois lados estão desalinhados:

Um professor observa que alunos têm dificuldade em aprender conceitos de sistemas distribuídos — um problema prático real. Mas se a literatura já contém diversas estratégias pedagógicas bem documentadas e avaliadas, talvez essa lacuna prática não represente uma **lacuna científica significativa**.

Por outro lado, um problema científico pode ser fascinante — "Como integrar inteligência artificial em sistemas de tomada de decisão organizacional de forma que os humanos mantenham agência?" — mas se nenhuma organização real enfrenta isso agora, falta o lado da **relevância prática**.

DSR exige que você articule claramente ambos os lados. Isso frequentemente aparece em duas frases distintas:

- **Problema prático:** O que está quebrado ou ineficiente no mundo real?
- **Lacuna científica:** O que não sabemos ainda ou que não está bem documentado na literatura?

**Exemplo concreto:** Um banco descobre que seus analistas de risco gastam horas revisando alertas de fraude que o sistema gera automaticamente. Muitos alertas são falsos positivos, causando fadiga. Os analistas precisam de uma forma mais eficiente de priorizar.

- **Problema prático:** Analistas perdem tempo com false positives; ameaças reais podem ser perdidas.
- **Lacuna científica:** "Não temos bem documentados os princípios de design para sistemas de priorização de alertas que equilibrem precisão, recall e carga cognitiva dos operadores em tempo real."

---

## Tipos de Artefatos

Um artefato em DSR não se restringe a código executável. **Múltiplas formas que um artefato pode tomar**. Compreender essa diversidade é importante porque muitos pesquisadores reduzem DSR a "criar um software", quando na verdade um artefato pode ser bem mais variado.

### Constructo
Um **conceito ou linguagem estruturada** que permite descrever um domínio. Um framework conceitual que organiza tipos de falhas em sistemas distribuídos. Uma taxonomia de estilos arquiteturais. A contribuição é uma forma nova e útil de pensar, não necessariamente uma implementação.

### Modelo
Uma **representação abstrata** que captura características essenciais. Um modelo de propagação de faults em redes de sensores. Um modelo comportamental de usuários. Aparecem frequentemente em forma de equações, diagramas ou descrições formais.

### Método
Um **processo prescritivo** para executar uma tarefa. Um método para elicitação de requisitos em ambientes ágeis. Um método para integração contínua. Proposto, validado e fundamentado em conhecimento de design.

### Algoritmo
Um **procedimento bem definido** para resolver uma classe de problemas computacionais. Um algoritmo de balanceamento de carga. Um algoritmo de compressão de dados. Tipicamente implementável.

### Arquitetura
Uma **estrutura de componentes** e suas relações. Uma arquitetura de microsserviços. Uma arquitetura de processamento de eventos. Oferece padrão reutilizável.

### Framework
Um **conjunto estruturado** de conceitos e processos instanciáveis em diferentes contextos. Um framework para maturidade DevOps. Um framework para integração humano-IA. Mais abstrato que implementação específica.

### Protótipo / Instância
Uma **realização concreta** de um ou mais dos anteriores. Uma implementação funcional demonstrando novo padrão.

### Sistema Computacional
Um **software completo**, tipicamente construído para contexto específico. Um sistema de gestão de aprendizagem. Um sistema de CRM.

**Importante:** Diferentes tipos de artefatos requerem diferentes estratégias de avaliação. Um algoritmo é avaliado diferentemente de um método. Uma arquitetura é avaliada diferentemente de um constructo. Confundir os tipos leva a avaliações inadequadas.

---

## Do Artefato ao Conhecimento: Contribuição Científica

Esse é talvez o ponto mais crítico e frequentemente negligenciado. **Construir um artefato não é, por si, contribuição científica.** A contribuição emerge quando aquela construção e sua avaliação produzem **conhecimento que transcende o artefato específico**.

### Exemplo: Sistema de Recomendação

Uma pesquisadora implementa sistema de recomendação para e-books. Usa collaborative filtering com adaptações para dados esparsos. Treina em dados históricos, valida com métricas padrão, faz deploy. Funciona bem.

**Sem contribuição científica:** "Implementamos um sistema de recomendação com estas características e teve estas métricas em produção."

**Com contribuição científica:** "Em contextos de dados esparsos combinados com heterogeneidade de preferências (como em bibliotecas públicas), certos princípios de design — regularização adaptativa, feedback implícito com ponderação temporal, diversificação — produzem melhores resultados que abordagens genéricas. Portanto, estas são as dimensões de design relevantes para contextos similares."

### Formas de Conhecimento de Design

**Design Principles** — Diretrizes sobre como construir artefatos similares. "Em sistemas de detecção de anomalias onde padrões normais evoluem, incorporar retraining periódico e feedback de especialistas melhora significativamente valor prático." Não é característica do artefato; é princípio transferível.

**Design Patterns** — Soluções recorrentes para problemas específicos. "Circuit breaker pattern" em sistemas distribuídos. Documentar com rigor significa: quando aplicável, que trade-offs produz, sob que condições falha.

**Taxonomies e Typologies** — Organizam espaço de soluções possíveis. Tipologia de estratégias de cache em edge computing, articulando dimensões relevantes e trade-offs.

**Process Knowledge** — Como executar efetivamente uma classe de tarefas. Um processo para migração de legacies para microsserviços baseado em múltiplos contextos.

**Theoretical Insights** — Entendimentos sobre por que certos designs funcionam melhor. Em sistemas críticos, descentralização reduz latência mas aumenta complexidade operacional.

---

## Conexões com Outros Capítulos

- **Capítulo 2** oferece fundação teórica para ciência do artificial
- **Capítulo 4-5** estruturam como operacionalizar problema e artefato
- **Capítulo 7** oferece orientações detalhadas para extrair conhecimento

---

## Resumo

| Aspecto | Definição |
|--------|-----------|
| **Problema Prático** | O que está quebrado/ineficiente no mundo real |
| **Lacuna Científica** | O que não sabemos/não está documentado |
| **Artefato** | Coisa construída (código, método, modelo, framework) |
| **Design Knowledge** | Princípios, patterns, diretrizes transferíveis |
| **Contribuição Científica** | Conhecimento que transcende artefato específico |

---

## Exercício Correspondente

Trabalhe o **Exercício 1** (Identificação de Problema) e **Exercício 4** (Extração de Conhecimento) do arquivo de exercícios práticos.

---

**Anterior:** [Capítulo 2: Fundamentos](02_fundamentos_epistemologicos.md)  
**Próximo:** [Capítulo 4: Processo DSRM →](04_processo_dsrm.md)
