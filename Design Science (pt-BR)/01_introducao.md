---
title: "Design Science Research: Introdução"
description: "Por que Design Science Research importa em Computação e como se diferencia de engenharia"
author: "Carlos Quintella"
date: 2026-09-18
tags: [DSR, fundamentos, pesquisa]
---

# Capítulo 1: Introdução

## O que é Design Science Research?

A ciência não se restringe a explicar como o mundo funciona. Ela também pode investigar sistematicamente como construir artefatos que resolvam problemas práticos de forma cientificamente rigorosa. Essa é a essência de **Design Science Research (DSR)**, uma perspectiva de pesquisa que ganhou relevância particular nas áreas de Engenharia, Computação e Sistemas de Informação.

Quando um pesquisador implementa um sistema, cria um algoritmo ou propõe uma arquitetura, ele naturalmente está resolvendo um problema. Mas nem todo artefato produzido constitui pesquisa científica. A diferença fundamental reside em como o problema foi identificado, como os requisitos foram justificados, como o artefato foi construído, como foi avaliado e, especialmente, que conhecimento generalizável foi produzido a partir dessa construção e avaliação.

## Por que Não é Simplesmente Engenharia?

A primeira confusão que surge é: "Se estou construindo algo, não estou fazendo engenharia?" A resposta é nuançada.

**Engenharia** responde à pergunta: "Como resolver este problema específico?" Um engenheiro desenha um edifício, resolve. Um engenheiro de software implementa um sistema, resolve. O foco é na solução prática do problema imediato.

**Design Science Research** também constrói coisas, mas faz uma pergunta diferente: "Como construir uma solução que, quando estudada cuidadosamente, produz conhecimento que vale para uma classe mais ampla de problemas?" O foco é não apenas na solução, mas no **conhecimento extraído daquela solução** que pode ser transferido a outros contextos.

A diferença é sutil mas crucial. Uma dissertação que relata "implementamos um sistema de recomendação e funcionou bem" é desenvolvimento competente. Uma dissertação que relata "implementamos um sistema de recomendação e, através de sua construção e avaliação rigorosa, aprendemos que em contextos de dados esparsos, certos princípios de design produzem melhor resultado, portanto estes princípios podem guiar futuros sistemas similares" é pesquisa.

## Duas Histórias: Desenvolvimento vs. Pesquisa

### História 1: Apenas Desenvolvimento

Um aluno é designado a resolver um problema em uma organização. A organização tem muitos alertas de segurança, os analistas gastam tempo filtrando false positives, e os alertas reais são perdidos no ruído.

O aluno implementa um sistema de priorização usando machine learning. Treina em dados históricos, valida com métricas padrão de classificação (acurácia, precisão, recall), faz o deploy em produção. Os alertas reduzem em 30%, os analistas reportam melhora, e o projeto é considerado sucesso.

O aluno escreve uma dissertação: "Desenvolvemos um sistema de triagem de alertas de segurança usando machine learning. O sistema alcança 88% de acurácia e reduz em 30% a carga dos analistas. Conclusão: sistema funciona e é útil."

**Isso é desenvolvimento bem executado, mas não é necessariamente pesquisa.**

### História 2: Pesquisa

O mesmo aluno começa diferente. Antes de qualquer implementação:

Ele documenta cuidadosamente **qual é o problema prático**: analistas de segurança em um banco enfrentam sobrecarga de false positive alerts, resultando em fadiga, redução de efetividade, e custo operacional alto.

Ele identifica **qual é a lacuna científica**: embora haja literatura sobre detecção de ameaças, há lacuna em conhecimento sistemático sobre como desenhar sistemas que balanceiem precisão técnica, recall de ameaças reais, e carga cognitiva dos operadores em contextos com extremo volume de dados.

Ele justifica seus **requisitos de design**: baseado em entrevistas com stakeholders reais (analistas, gerentes de SOC), em revisão de literatura sobre sobrecarga cognitiva, e em métricas que importam na prática (não apenas acurácia, mas também tempo de análise, satisfação do usuário).

Ele **desenha e desenvolve iterativamente**: começa com prototipagem rápida, testa com usuários, refina, repete. Cada decisão é justificada — por que aquele algoritmo? Por que aquela interface? Que trade-offs?

Ele **avalia rigorosamente**: não apenas em laboratório (dados históricos), mas também em ambiente real com usuários reais. Mede múltiplas dimensões — eficácia técnica, mas também impacto na prática, usabilidade, confiança do usuário.

Finalmente, ele **extrai conhecimento**: "De nossa construção e avaliação cuidadosa deste sistema, emergem design principles para sistemas de triagem sob volume extremo. Especificamente: (1) filtros determinísticos como primeira camada reduzem significativamente o volume sem sofisticação computacional; (2) machine learning adaptativo que retreina com feedback de usuários é crítico; (3) explicabilidade de decisões melhora significativamente confiança do usuário. Estes princípios podem guiar pesquisadores e práticos em futuros sistemas similares."

**Isso é pesquisa em Design Science Research.**

A diferença não está no artefato (ambas implementaram sistema). A diferença está em rigor na identificação do problema, em justificação de design, em avaliação múltipla, e em extração de conhecimento transferível.

## Por que Design Science Research Importa em Computação?

Computação é fundamentalmente engenharia — nós criamos coisas. Mas isso não significa que toda criação é pesquisa. Design Science Research oferece um caminho para transformar construção em pesquisa científica legítima.

Sem DSR, dissertações em Computação frequentemente reduzem-se a "implementamos X e alcançamos Y métrica". Com DSR, dissertações podem articular: "Investigamos como construir X, e descobrimos Z princípios que importam para essa classe de problemas."

O objeto de investigação muda de "o sistema específico" para "conhecimento sobre como construir sistemas dessa classe". É essa mudança de foco que transforma desenvolvimento em pesquisa.

## Objetivo Deste Material

O objetivo deste material é capacitar pesquisadores e alunos a compreender Design Science Research não como um modo de "validar" uma implementação já pronta, mas como um processo sistemático onde a construção do artefato e a geração de conhecimento científico são indissociáveis.

Ao longo dos próximos capítulos, você aprenderá:

- **Fundamentos:** Por que Design Science é uma ciência válida (Capítulo 2)
- **Conceitos:** Como identificar problemas e artefatos apropriados (Capítulo 3)
- **Processo:** Como estruturar uma pesquisa DSR usando metodologias estabelecidas (Capítulos 4-5)
- **Avaliação:** Como validar artefatos rigorosamente (Capítulo 6)
- **Conhecimento:** Como extrair design principles e insights transferíveis (Capítulo 7)
- **Atualidade:** Como engajar com desenvolvimentos contemporâneos em DSR (Capítulo 8)

---

## Conexões com Outros Capítulos

- **Capítulo 2** oferece fundação teórica para por que DSR é ciência legítima
- **Capítulo 3** detalha como formular problemas e reconhecer artefatos
- **Capítulo 4** estrutura o processo passo-a-passo
- **Capítulo 6** oferece orientações para avaliação rigorosa

---

## Resumo

| Conceito | Definição |
|----------|-----------|
| **Design Science Research** | Investigação sistemática de como construir artefatos que resolvem problemas práticos e produzem conhecimento científico |
| **Artefato** | Coisa que você constrói (software, método, modelo, framework) |
| **Pesquisa vs. Desenvolvimento** | Pesquisa produz conhecimento transferível; desenvolvimento resolve problema específico |
| **Lacuna Científica** | Conhecimento que não existe ou está incompleto na literatura |
| **Design Knowledge** | Conhecimento sobre como construir certa classe de artefatos |

---

## Exercício Correspondente

Trabalhe o **[Exercício 1](../exercicios_praticos.md#exercício-1-identificação-de-problema-e-lacuna-científica)** do arquivo de exercícios práticos. Ele pedirá que você identifique um problema prático e uma lacuna científica em um cenário proposto.

---

## Leitura Complementar

- Hevner et al. (2004) — Artigo seminal definindo design science em SI
- Simon (1996) — "The Sciences of the Artificial" (fundação teórica)
- Peffers et al. (2007) — Introdução ao DSRM

---

**Próximo:** [Capítulo 2: Fundamentos Epistemológicos →](02_fundamentos_epistemologicos.md)
