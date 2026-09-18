# Exercícios Práticos em Design Science Research

## Exercício 1: Identificação de Problema e Lacuna Científica

### Objetivo

Aprender a distinguir entre um problema prático vago e uma formulação rigorosa que articule claramente a lacuna entre o que existe (na prática e no conhecimento) e o que deveria existir.

### Cenário

Você trabalha em uma universidade com um programa de educação a distância. Professores reclamam que muitos alunos não completam as disciplinas. A taxa de evasão é de 35%, considerada alta. Você foi convidado a pesquisar isso sob perspectiva DSR.

### Tarefa

Articular um problema de pesquisa DSR bem formulado que inclua:

**1. O problema prático:** Descreva o que está acontecendo no mundo real, quem é afetado, qual é o impacto e por que isso importa.

**2. O problema científico (lacuna de conhecimento):** Descreva o que não sabemos sobre este problema. O que a literatura deixa em aberto? Qual conhecimento, método ou artefato está faltando?

**3. Uma justificativa de por que esses dois problemas estão conectados:** Explique como resolver a lacuna científica poderia ajudar a resolver o problema prático.

### Resposta Esperada (Exemplo)

**Problema Prático:** Instituições de educação a distância enfrentam taxas de evasão entre 30-50%, significativamente maiores que em educação presencial. No caso desta universidade, 35% dos alunos matriculados não completam a disciplina. Impacto: perda de receita, reputação da instituição, desperdício de investimento em desenvolvimento de conteúdo, desapontamento para alunos que investiram dinheiro e tempo.

**Lacuna Científica:** Embora haja literatura sobre fatores que predizem evasão (baixo engajamento, falta de interação social, sobrecarga de trabalho), há menos conhecimento sobre como desenhar **intervenções específicas de design pedagógico e tecnológico** que efetivamente reduzam evasão em ambientes com restrições de recursos (muitos alunos, orçamento limitado, ferramentas genéricas). A maioria dos estudos sobre redução de evasão focam em análise preditiva (identificar alunos em risco) mas não em design de sistemas que *impeçam* a situação de risco. Falta, portanto, conhecimento de design sobre "Como estruturar uma experiência de aprendizagem a distância que mantenha alunos engajados, especialmente aqueles com perfil de risco?"

**Conexão:** Ao desenhar uma solução (artefato) que aborde a lacuna científica — por exemplo, um método de design instrucional incorporando elementos de gamificação, comunidade, e suporte psicossocial — você não apenas resolve o problema prático (reduz evasão), mas produz conhecimento sobre quais elementos de design são críticos neste contexto.

---

## Exercício 2: Definição de Objetivos de Design

### Objetivo

Aprender a transformar um problema vago em objetivos de design específicos, mensuráveis e traçáveis.

### Cenário

Você está pesquisando segurança de aplicações web em uma grande empresa de tecnologia. Você identificou que desenvolvedores frequentemente cometem erros de segurança (injeção SQL, XSS, autenticação fraca) durante o desenvolvimento, e esses erros só são descobertos em revisão de código ou teste de segurança, tardiamente no ciclo. O custo de corrigir é alto.

Sua ideia é criar uma ferramenta (IDE plugin) que forneça feedback em tempo real sobre vulnerabilidades de segurança conforme o desenvolvedor escreve código.

### Tarefa

Defina 4-5 objetivos de design que especifiquem:
- **O quê:** qual aspecto da solução está sendo otimizado
- **Para quem:** qual stakeholder é afetado
- **Métrica:** como você mediria sucesso
- **Meta:** qual valor você quer alcançar

### Resposta Esperada (Exemplo)

**Objetivo 1 (Eficácia de Detecção):** O plugin deverá detectar vulnerabilidades conhecidas de segurança com precisão ≥ 90% e recall ≥ 85% em código JavaScript/TypeScript, validado em um dataset de 500 trechos de código contendo vulnerabilidades conhecidas (OWASP Top 10).

**Objetivo 2 (Usabilidade para Desenvolvedores):** Desenvolvedores deverão ser capazes de compreender o alerta de segurança (qual é o problema, por que é problema, como corrigi-lo) em menos de 2 minutos, validado através de teste de compreensão com 10 desenvolvedores junior.

**Objetivo 3 (Performance):** O plugin não deverá degradar significativamente a performance da IDE. Latência para análise incremental deverá ser < 500ms para mudanças de uma função, validado em máquinas com especificação padrão de desenvolvimento.

**Objetivo 4 (Adoção):** Após 3 meses de uso opcional, ≥ 70% dos desenvolvedores que têm acesso ao plugin deverão usá-lo regularmente (≥ 3 vezes por semana), indicando que a ferramenta é suficientemente útil que desenvolvedores escolhem usá-la.

**Objetivo 5 (Impacto na Prática):** Em produção, a taxa de vulnerabilidades de segurança relacionadas às categorias detectadas pelo plugin deverá reduzir ≥ 40% comparado ao período pré-plugin (comparando commits 6 meses antes vs. 6 meses depois).

### Discussão

Notar que os objetivos cobrem três dimensões: funcionalidade técnica (detecção), usabilidade (compreensão), performance (overhead), e impacto prático (adoção, redução de vulnerabilidades). Nem todos os objetivos são quantitativos; alguns são qualitativos, mas todos são específicos e mensuráveis.

---

## Exercício 3: Desenho de Avaliação Experimental

### Objetivo

Aprender a estruturar um experimento que forneça evidência rigorosa sobre se um artefato atinge seus objetivos.

### Cenário

Você desenvolveu um **método de elicitação de requisitos para sistemas de IA** dirigido a stakeholders não-técnicos (gerentes de negócio, usuários finais). O método consiste em uma série de workshops estruturados onde facilitadores guiam stakeholders através de exercícios específicos para articular o que o sistema de IA deveria fazer.

Sua hipótese é que usar este método produz requisitos mais completos e com menos ambiguidade que o método tradicional (entrevistas ad-hoc e workshops não estruturados).

### Tarefa

Desenhe um experimento para validar esta hipótese. Seu desenho deve incluir:

1. **Variável independente (o que você manipula):** Que você vai variar no experimento?
2. **Variável dependente (o que você mede):** Qual é o resultado que você quer avaliar?
3. **Variáveis de controle:** Que características você manterá constantes ou controlará?
4. **Participantes:** Quem participará? Como será a amostra?
5. **Procedimento:** Qual é o passo-a-passo do experimento?
6. **Análise:** Como você vai interpretar os resultados?

### Resposta Esperada (Exemplo)

**Variável Independente:** Método de elicitação de requisitos. Condição 1: Método tradicional (entrevistas e workshops ad-hoc). Condição 2: Seu método estruturado.

**Variável Dependente:** Qualidade dos requisitos elicitados, medida através de: (a) completude — quantos requisitos foram capturados comparado a um checklist de domínio; (b) clareza — score de ambiguidade quando requisitos são lidos por terceiros; (c) rastreabilidade — quão bem os requisitos rastreiam para objetivos de negócio.

**Variáveis de Controle:** Domínio de aplicação (vamos usar 3 casos de uso similares de IA em contextos corporativos), duração total do processo de elicitação (fixado em 6 horas), experiência dos facilitadores (ambos metódicos e experientes), tipo de stakeholders (mistura de gerentes e usuários finais).

**Participantes:** 2 grupos de 5 stakeholders cada, recrutados de 2 contextos corporativos diferentes, balanceados em experiência com IA. Um grupo usa Método Tradicional, outro usa Seu Método. Idealmente, você replicaria com múltiplos pares de grupos para aumentar confiabilidade.

**Procedimento:** 
- Semana 1: Treinamento dos facilitadores em ambos os métodos.
- Semana 2: Grupo A participa do método tradicional; Grupo B participa do seu método. Ambos recebem o mesmo briefing sobre o contexto de negócio.
- Semana 3: Requisitos elicitados são documentados por um secretário neutro.
- Semana 4: Um avaliador independente (cego para qual método foi usado) avalia requisitos usando uma rubrica predefinida para completude, clareza e rastreabilidade.
- Semana 5: Você compara os escores entre grupos e analisa estatisticamente.

**Análise:** Usar testes estatísticos apropriados (t-test se comparando dois grupos, ANOVA se múltiplos grupos). Reportar magnitude de efeito, não apenas significância. Interpretar não apenas números, mas também quais tipos de requisitos cada método captura melhor.

---

## Exercício 4: Extração de Conhecimento de Design

### Objetivo

Aprender a transformar um artefato específico em princípios de design transferíveis.

### Cenário

Você conduziu uma pesquisa completa DSR onde desenvolveu um **sistema de coaching de performance para vendedores**, que fornece feedback em tempo real baseado em análise de chamadas de venda. O sistema registra chamadas, transcreve com IA, analisa a conversa contra padrões de vendas efetivas, e fornece feedback.

Você avaliou o sistema com 20 vendedores durante 3 meses. Resultados: vendedores que usaram o sistema regularmente aumentaram taxa de fechamento em média 18%, reduziram ciclo de venda em 12%, e relataram maior confiança. Mas houve uma descoberta interessante: o sistema foi especialmente efetivo para vendedores junior (sem experiência), com ganho de 28%, enquanto para vendedores sênior o ganho foi apenas 8%.

### Tarefa

Extraia 3-4 design principles de suas descobertas. Cada princípio deve:
- **Nomear explicitamente a dimensão de design** que está sendo recomendada
- **Especificar as condições** sob as quais o princípio aplica
- **Articular o efeito esperado** (o que melhora)
- **Reconhecer trade-offs** (o que piora ou que cuidados tomar)
- **Sugerir como aplicar em novos contextos**

### Resposta Esperada (Exemplo)

**Design Principle 1 — Personalização Baseada em Experiência:**
Em sistemas de feedback de performance para aprendizagem profissional, a efetividade do coaching é significativamente maior quando a frequência, granularidade e tipo de feedback são adaptados ao nível de experiência do aprendiz. Especificamente, vendedores com < 1 ano de experiência beneficiam de feedback frequente e granular (após cada chamada, apontando padrões específicos de fala), enquanto vendedores com > 5 anos de experiência respondem melhor a feedback menos frequente focado em padrões emergentes ou oportunidades de inovação. 

*Efeito:* melhora de 20%+ em adopção do sistema e em outcomes (taxa de fechamento, ciclo de venda).

*Trade-off:* sistemas personalizados por experiência exigem lógica mais complexa para calibrar. O custo de desenvolvimento aumenta. Além disso, há risco de que vendedores sênior percebam feedback granular como microgerenciamento.

*Aplicação em novos contextos:* Ao desenhar sistemas de coaching em outros domínios (atendimento ao cliente, negociação, ensino), considere não um único modelo de feedback, mas múltiplos modelos ajustados por experiência. Isso pode ser implementado através de testes iniciais para categorizar nível de experiência, seguido de dinâmica de feedback adaptativa.

**Design Principle 2 — Transparência do Algoritmo:**
Quando um sistema de IA fornece feedback crítico para a performance de um profissional (ex: coaching, avaliação), a aceitação e efetividade do sistema aumentam significativamente quando o profissional compreende em detalhe por que o sistema forneceu aquele feedback específico. No seu caso, quando o sistema não apenas disse "você deveria usar mais perguntas abertas", mas explicou "você fez 12 perguntas fechadas nesta chamada; padrão de vendedores bem-sucedidos é 6-8 fechadas e 8-12 abertas", a confiança aumentou e comportamento mudou mais rapidamente.

*Efeito:* aumento de confiança do usuário, velocidade de aprendizagem, e resultado final.

*Trade-off:* explicações demandam mais processamento e mais cuidado na formulação. Há risco de que explicações ruins (imprecisas ou desencorajadoras) causem dano.

*Aplicação em novos contextos:* Ao desenhar feedback de IA para profissionais, invista em explicabilidade. Não apenas o sistema recomenda ações; ele explica a evidência por trás da recomendação e qual padrão de desempenho ele está tentando atingir.

**Design Principle 3 — Feedback Iterativo vs. Episódico:**
Sistemas de coaching produzem melhor outcomes quando combinam feedback episódico (reflexão estruturada ao fim de ciclos, ex: ao fim de uma semana) com feedback iterativo (em-tempo-real, ex: sugestões durante ou imediatamente após uma chamada). Feedback apenas iterativo pode causar fadiga e perda de confiança. Feedback apenas episódico não captura contexto suficiente e deixa o profissional sem oportunidade de aplicar feedback imediatamente.

*Efeito:* melhora significativa em retenção de aprendizado e comportamento mudando.

*Trade-off:* requer mais engenharia (dois ciclos de feedback em vez de um). Pode ser experimentalmente complexo de calibrar.

*Aplicação:* Ao desenhar sistemas de coaching ou avaliação de performance, considere combinar feedback real-time com reflexão estruturada periódica. Evite escolher apenas um.

---

## Exercício 5: Estudo de Caso Completo em Grupo

### Objetivo

Sintetizar tudo que foi aprendido: problema, artefato, objetivos, design, avaliação, e conhecimento.

### Cenário

Você foi convidado por uma prefeitura para pesquisar como melhorar a eficiência de coleta de lixo. Atualmente, caminhões saem de garagens com rotas pré-definidas. Há desperdício: alguns trechos são visitados quando estão vazios, enquanto outros ficam cheios. Custos de combustível e tempo são altos.

Você identificou que dados em tempo real (sensores de enchimento em caixas de lixo) existem, mas não são usados. A ideia é um sistema que otimize rotas em tempo real usando esses dados.

### Tarefa em Grupo

Estruture um projeto DSR completo. Trabalhe em grupos de 3-4 pessoas. Cada grupo apresenta:

1. **Definição do Problema:** Qual é o problema prático e a lacuna científica?

2. **Objetivos de Design:** Que o sistema deve alcançar? (Listar 4-5 com métricas)

3. **Artefato Proposto:** Que você construirá? Arquitetura de alto nível.

4. **Plano de Design:** Como você iterará? Que ciclos de prototipagem?

5. **Plano de Avaliação:** Como validará que atinge os objetivos? Que experimento?

6. **Conhecimento Esperado:** Que design principles você espera extrair?

7. **Contexto Real:** Como isso seria testado com a prefeitura real?

### Discussão Esperada

Discussão após apresentação:
- Os objetivos são mensuráveis e traçáveis?
- A avaliação é rigorosa (não apenas "funcionou bem")?
- Há clareza sobre que é o artefato vs. que é a contribuição científica?
- Os design principles extrapolam além deste contexto específico?

---

## Exercício 6: Revisão Crítica de um Trabalho DSR (Fictício)

### Objetivo

Aprender a avaliar criticamente pesquisas DSR, identificando forças e fraquezas.

### Cenário

Você recebe um resumo de dissertação para avaliar em uma banca. Leia e critique:

---

**Título:** "Um Sistema de Recomendação de Cursos para Plataformas de Educação Contínua"

**Resumo:** Este trabalho propõe um sistema de recomendação baseado em collaborative filtering para sugerir cursos a usuários em plataformas de educação contínua. Implementamos o sistema em Python usando bibliotecas scikit-learn e Flask. O sistema foi treinado em dados históricos de 10,000 usuários e 500 cursos. Avaliamos o sistema usando RMSE (Root Mean Square Error) e MAE (Mean Absolute Error) em um conjunto de teste separado, obtendo RMSE de 0.82 e MAE de 0.65. Concluímos que o sistema funciona bem e recomendamos seu uso em produção.

---

### Tarefa

Critique este trabalho sob perspectiva DSR respondendo:

1. **Qual é o problema prático identificado?** É claro e bem justificado?

2. **Qual é a lacuna científica?** O trabalho articula o que não se sabe?

3. **Que é o artefato?** É claro? Que tipo de artefato é?

4. **Os objetivos de design estão articulados?** Ou apenas métricas genéricas foram escolhidas?

5. **A avaliação é rigorosa?** Que estratégias foram usadas? Faltam perspectivas?

6. **Há clareza sobre a contribuição científica?** O que aprendemos que transcende este sistema específico?

7. **Que perguntas faltam ser respondidas?**

### Resposta Esperada (Exemplo de Crítica)

*Pontos Fracos:*

- Nenhuma articulação clara de que é o problema prático que o sistema resolve. "Um sistema de recomendação de cursos" não é um problema; é uma solução. Qual é o problema real? Usuários não encontram cursos relevantes? Há abandonos porque as recomendações são ruins?

- A lacuna científica não está articulada. Recomendação baseada em collaborative filtering é conhecida. Há muita literatura. O que especificamente este trabalho adiciona?

- Métricas (RMSE, MAE) são métricas técnicas de acurácia de predição. Mas não há articulação de por que essas são as métricas relevantes. Seria possível ter RMSE baixo mas recomendações que não aumentem engajamento do usuário? Sim. Então por que RMSE é a métrica que importa?

- Não há avaliação naturalística. Apenas laboratório (métricas de teste). Não há evidência de que usuários reais encontram as recomendações úteis.

- Não há clareza sobre que conhecimento de design foi produzido. "Collaborative filtering funciona para recomendação de cursos" já era esperado. Qual é a novidade?

*Pontos que Faltam:*

- Definição clara do contexto e do problema (quais usuários, qual plataforma, que tipo de cursos).

- Revisão de literatura posicionando o trabalho no que já existe.

- Objetivos de design específicos para este contexto (ex: "usuários devem encontrar ≥ 80% relevância percebida em recomendações").

- Avaliação com usuários reais (ex: A/B test em produção, feedback de usuários).

- Extração de princípios de design (ex: "Em plataformas de educação contínua com alta diversidade de usuários e cursos, a incorporação de feedback implícito reduz significativamente falsos positivos em recomendação").

*Recomendação:* Trabalho como está é desenvolvimento competente, mas não é pesquisa em Design Science Research. Para ser DSR, seria necessário: (1) articular claramente que problema prático motivou o trabalho, (2) justificar que este problema representa uma lacuna científica, (3) desenhar objetivos que importam na prática (não apenas acurácia técnica), (4) executar avaliação que inclua usuários reais e impacto prático, (5) refletir sobre conhecimento de design transferível.

---

## Exercício 7: Reflexão Pessoal — Seu Próprio Projeto DSR

### Objetivo

Começar a estruturar sua própria pesquisa sob lente DSR.

### Tarefa

Se você tem uma ideia de pesquisa ou dissertação em mente, responda:

1. **Qual é meu problema prático?** Descreva em detalhe o que não funciona bem no mundo real. Para quem é um problema? Que impacto tem?

2. **Qual é minha lacuna científica?** O que não sabemos sobre este problema? Que literatura existe? Onde há oportunidade?

3. **Que tipo de artefato farei?** Software? Método? Framework? Modelo? Algoritmo? Por quê?

4. **Quais serão meus 4-5 objetivos de design?** Especifique com métricas.

5. **Como vou avaliar?** Que estratégias (artificial/naturalística, formativa/somativa)?

6. **Que conhecimento de design espero extrair?** Que princípios, padrões, ou insights?

7. **Como isso conecta com minha carreira?** Por que esta pesquisa importa para mim?

Não há resposta "correta" — a reflexão em si é o valor.
