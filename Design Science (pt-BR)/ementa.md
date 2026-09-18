
Sim. Para uma aula atual de **Design Science Research (DSR)** em Computação/Sistemas de Informação, eu não ficaria apenas no modelo clássico “construir um artefato e avaliá-lo”. Hoje vale ensinar também **como transformar o artefato em contribuição científica**, como justificar requisitos, como garantir transparência/reprodutibilidade e como lidar com IA generativa.

O núcleo ainda é bastante estável: identificar um problema relevante, definir objetivos para a solução, projetar e desenvolver o artefato, demonstrá-lo, avaliá-lo e comunicar os resultados — a sequência consagrada pelo DSRM de Peffers et al. ([Taylor & Francis Online](https://www.tandfonline.com/doi/abs/10.2753/MIS0742-1222240302?utm_source=chatgpt.com "A Design Science Research Methodology for Information Systems Research: Journal of Management Information Systems: Vol 24, No 3"))

### Ementa atualizada de Design Science Research

**Design Science Research: fundamentos, métodos e aplicações em Computação e Sistemas de Informação.** Paradigmas de pesquisa e distinção entre ciência comportamental, ciência natural e ciência do artificial. Fundamentos epistemológicos da Design Science. Problema de pesquisa e problema de design. Relevância, rigor e contribuição científica. Artefatos de pesquisa: constructos, modelos, métodos, frameworks, arquiteturas, algoritmos, instâncias e sistemas computacionais. Ciclos de Design Science Research. Design Science Research Methodology — DSRM. Construção e avaliação iterativa de artefatos. Definição de requisitos e objetivos de design. Design principles e design knowledge. Avaliação ex ante e ex post; avaliação artificial e naturalística. Validade, confiabilidade, transparência e reprodutibilidade em DSR. Relação entre teoria, artefato e contexto. Revisão sistemática da literatura e rastreabilidade entre evidências, requisitos, artefato e avaliação. Ciência aberta e documentação dos ciclos de projeto. Ética, sustentabilidade, valores dos stakeholders e responsible design. Aplicações contemporâneas de DSR em Inteligência Artificial, sistemas humano-IA e IA generativa. Estruturação e publicação de artigos, dissertações e teses baseados em Design Science Research.

Essa atualização é especialmente importante porque trabalhos recentes têm chamado atenção para **confiabilidade, transparência e rastreabilidade** do processo de DSR, e não apenas para a qualidade final do artefato. Um framework publicado no _Information Systems Journal_ em 2025, por exemplo, discute explicitamente a confiabilidade do artefato, dos métodos, das medidas e do conhecimento de design produzido. ([Wiley Online Library](https://onlinelibrary.wiley.com/doi/full/10.1111/isj.12564?utm_source=chatgpt.com "Reliability in design science research - Storey - 2025 - Information Systems Journal - Wiley Online Library")) Trabalhos recentes também associam DSR a ciência aberta, transparência e reprodutibilidade. ([ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0167923624000691?utm_source=chatgpt.com "Transparency in design science research - ScienceDirect"))

## Eu estruturaria uma aula de 4 horas assim

|Bloco|Tema|Conteúdo|
|---|---|---|
|1|O que é DSR|ciência natural × behavioral science × design science|
|2|Problema e artefato|problema prático, lacuna científica, artefatos e contribuições|
|3|Modelos clássicos|Hevner; Peffers/DSRM; ciclos de rigor, relevância e design|
|4|Construção|requisitos, objetivos de design, kernel theories, design principles|
|5|Avaliação|avaliação formativa/somativa, artificial/naturalística, métricas|
|6|Conhecimento científico|do artefato específico para conhecimento generalizável|
|7|DSR moderna|transparência, reprodutibilidade, ciência aberta, ética e GenAI|
|8|Prática|alunos desenham um projeto DSR completo|

A parte essencial da aula deve ser fazer o aluno perceber que:

> **“Eu desenvolvi um sistema” não caracteriza, por si só, Design Science Research.**

É preciso existir uma cadeia científica mais ou menos assim:

**Problema → conhecimento existente → requisitos → design → artefato → demonstração → avaliação → reflexão → conhecimento de design.**

Essa rastreabilidade está ganhando bastante atenção. Um trabalho de 2026, por exemplo, propõe integrar explicitamente revisão sistemática e PRISMA ao processo de DSR justamente para estabelecer uma cadeia rastreável entre **evidências → requisitos → artefato → avaliação → conhecimento de design**. ([ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2215016126002815?utm_source=chatgpt.com "The DSR-PRISMA protocol: Embedding systematic knowledge mapping into design science research for applied technology studies - ScienceDirect"))

### 1. Fundamentos que eu colocaria obrigatoriamente

Começaria com Herbert Simon e a ideia das **“sciences of the artificial”**: ciência não precisa apenas explicar aquilo que existe; pode investigar sistematicamente aquilo que **deveria ser construído para atingir determinado objetivo**.

A distinção didática funciona muito bem:

**Ciência tradicional**


`Como o mundo funciona?`

versus

**Design Science**

`Como podemos construir algo que resolva determinada classe de problemas?`

Mas o aluno precisa entender que DSR não é simplesmente engenharia.

Eu usaria:

**Engenharia**

`Problema → solução`

e:

**Design Science Research**

`Problema → conhecimento → artefato → avaliação → novo conhecimento`

Esse último elemento muda tudo.

### 2. O conceito de artefato

Vale dedicar um bom tempo a isso.

Um artefato DSR pode ser:

- constructo;
    
- modelo;
    
- método;
    
- algoritmo;
    
- framework;
    
- arquitetura;
    
- protocolo;
    
- processo;
    
- software;
    
- protótipo;
    
- sistema;
    
- ferramenta;
    
- linguagem;
    
- conjunto de design principles.
    

Por exemplo, em Segurança da Informação:

**Problema:** dificuldade de detectar movimentação lateral em redes corporativas.

**Artefato:** arquitetura de detecção baseada em graph neural networks.

Mas o artigo não deveria parar em:

> “Construímos uma GNN que detecta ataques.”

A contribuição poderia ser algo como:

> “Derivamos princípios de design para sistemas de detecção de movimentação lateral em redes corporativas heterogêneas.”

A segunda formulação começa a produzir **design knowledge** transferível.

### 3. O processo DSRM

Aqui eu ensinaria Peffers praticamente como o “algoritmo básico” da aula:

**1. Problem identification and motivation**

↓

**2. Define objectives for a solution**

↓

**3. Design and development**

↓

**4. Demonstration**

↓

**5. Evaluation**

↓

**6. Communication**

É um dos modelos de processo mais utilizados e continua aparecendo em trabalhos atuais. ([Springer](https://link.springer.com/article/10.1007/s41471-025-00233-6?utm_source=chatgpt.com "Design Science Across Disciplines: Building Bridges for Advancing Impactful Business Research | Schmalenbach Journal of Business Research | Springer Nature Link"))

Mas eu faria uma ressalva importante:

**não é necessariamente linear.**

Na prática:

`Design → avaliação → redesign → avaliação → redesign...`

é muito mais realista.

### 4. Os ciclos de Hevner

Essa parte eu considero obrigatória porque ajuda muito os alunos a entenderem uma tese DSR.

Eu apresentaria três ciclos:

**Relevance Cycle**

Ambiente real ↔ pesquisa

Quem precisa da solução?  
Qual é o problema real?  
Quais são as restrições?

**Rigor Cycle**

Base de conhecimento ↔ pesquisa

Que teorias existem?  
Que métodos existem?  
Que artefatos anteriores existem?

**Design Cycle**

Construção ↔ avaliação.

É o ciclo iterativo onde o artefato evolui.

Didaticamente:

```text
             BASE DE CONHECIMENTO
             teorias / métodos
                    ↕
                 RIGOR
                    ↕
AMBIENTE ← RELEVÂNCIA → DESIGN
 problemas              ↕
 stakeholders        construir
 contexto            avaliar
                        ↕
                     artefato
```

### 5. A questão mais importante: avaliação

Aqui costuma estar uma das fraquezas de dissertações DSR.

Não basta dizer:

> “O protótipo funcionou.”

Pergunte:

**Funcionou em relação a quê?**

Se o requisito era diminuir latência:

`latência antes × latência depois`

Se era melhorar classificação:

`precision / recall / F1 / ROC-AUC`

Se era melhorar usabilidade:

`SUS / experimentos / entrevistas`

Se era arquitetura:

`performance / escalabilidade / disponibilidade / segurança`

Se era método:

`comparação com baseline / especialistas / estudo de caso`

Ensine explicitamente:

**Objetivo → critério → métrica → experimento → evidência.**

Essa relação deveria aparecer quase como uma matriz na pesquisa.

### 6. A distinção que eu enfatizaria muito

Existem pelo menos três coisas diferentes:

**Artefato**

> O que construí.

**Avaliação**

> Evidência de que funciona.

**Contribuição científica**

> O que aprendemos com sua construção e avaliação.

Por exemplo:

Artefato:

> algoritmo de alocação dinâmica de recursos em edge computing.

Resultado:

> reduziu latência em 22%.

Design knowledge:

> sob determinadas características de carga e topologia, a descentralização da decisão produz determinado efeito; daí podem surgir princípios ou regras de design.

É aí que aparece a pesquisa.

## O que eu acrescentaria como atualização 2024–2026

Eu criaria um bloco final chamado **“DSR contemporânea”**.

Primeiro, **transparência e reprodutibilidade**. A literatura recente tem insistido em documentar decisões, versões do artefato, métodos, dados, instrumentos e critérios de avaliação, aproximando DSR das práticas de Open Science. ([ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0167923624000691?utm_source=chatgpt.com "Transparency in design science research - ScienceDirect"))

Segundo, **Value-Sensitive Design / Responsible Design**. Não avaliar apenas:

`funciona?`

mas também:

`para quem funciona?`

`quem é afetado?`

`quais valores estão incorporados no artefato?`

Há exemplos recentes integrando explicitamente métodos de Value-Sensitive Design a projetos DSR e avaliando o artefato com stakeholders reais. ([Springer](https://link.springer.com/article/10.1007/s12599-024-00873-8?utm_source=chatgpt.com "Advancing Customer Feedback Systems with Blockchain | Business & Information Systems Engineering | Springer Nature Link"))

Terceiro, **IA e sistemas humano-IA**. DSR está sendo utilizada justamente para investigar não apenas modelos de IA, mas a interação entre tecnologia, seres humanos, decisões e organizações. Uma linha recente trata explicitamente o design de sistemas humano-IA sob essa perspectiva. ([ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0167923624000630?utm_source=chatgpt.com "The design of human-artificial intelligence systems in decision sciences: A look back and directions forward - ScienceDirect"))

Quarto, **IA generativa dentro do próprio processo de DSR**. Já aparecem pesquisas usando GenAI para auxiliar construção de artefatos e processos científicos; há, por exemplo, trabalho DSR de 2024 sobre automação de revisão sistemática com IA generativa. ([JMIR Medical Education](https://mededu.jmir.org/2024/1/e48949?utm_source=chatgpt.com "JMIR Medical Education - Cocreating an Automated mHealth Apps Systematic Review Process With Generative AI: Design Science Research Approach")) E trabalhos mais recentes já começam a discutir artefatos com elementos de auto-design e evolução apoiados por IA. ([Springer](https://link.springer.com/article/10.1007/s43681-025-00965-5?utm_source=chatgpt.com "Toward an artifact that designs itself: generative design science research approach | AI and Ethics | Springer Nature Link"))

Isso abre uma discussão excelente para sala:

> Se a IA ajuda a gerar requisitos, código, arquitetura e testes, **onde está a contribuição do pesquisador?**

A resposta provavelmente vai estar cada vez menos em simplesmente “construir o software” e mais em **formular, justificar e validar conhecimento de design**.

## Exercício que eu usaria na aula

Daria um problema próximo à área de TI:

> Uma organização possui milhares de eventos de segurança produzidos por firewalls, endpoints e servidores. Os analistas têm dificuldade para priorizar incidentes.

E pediria aos grupos que produzissem:

**Problema de pesquisa → objetivo → artefato → requisitos → método de construção → demonstração → métricas → método de avaliação → possível contribuição científica.**

Por exemplo:

```text
Problema
    ↓
Sobrecarga dos analistas SOC
    ↓
Objetivo
    ↓
Melhorar priorização de alertas
    ↓
Artefato
    ↓
Modelo + arquitetura de triagem
    ↓
Design
    ↓
LLM + regras + threat intelligence
    ↓
Avaliação
    ↓
Dataset histórico + analistas
    ↓
Métricas
    ↓
precision, recall, tempo de triagem,
carga cognitiva
    ↓
Conhecimento produzido
    ↓
Design principles para sistemas
de triagem SOC apoiados por IA
```

Esse exemplo permite ensinar praticamente **DSR inteira em uma única atividade**.

### Bibliografia essencial

Eu dividiria a bibliografia em duas camadas. Na clássica: **Herbert Simon**, _The Sciences of the Artificial_; **Hevner et al. (2004)**, _Design Science in Information Systems Research_; **Peffers et al.**, _A Design Science Research Methodology for Information Systems Research_; e trabalhos de **Gregor & Hevner** sobre posicionamento e contribuição do conhecimento em DSR.

Na parte contemporânea, acrescentaria os trabalhos sobre **transparência em DSR**, **reliability in design science research**, integração com ciência aberta e os trabalhos recentes sobre DSR + IA/GenAI. A discussão recente de confiabilidade é especialmente interessante porque desloca a avaliação de “o artefato funcionou?” para a confiabilidade do **artefato, métodos, medidas e design knowledge** produzido. ([Wiley Online Library](https://onlinelibrary.wiley.com/doi/full/10.1111/isj.12564?utm_source=chatgpt.com "Reliability in design science research - Storey - 2025 - Information Systems Journal - Wiley Online Library"))

Para uma disciplina de Computação, eu faria uma ementa com aproximadamente **60% metodologia DSR + 25% avaliação experimental + 15% tópicos contemporâneos**, porque a grande dificuldade dos alunos normalmente não é imaginar um artefato: é demonstrar **por que aquilo é pesquisa científica e não apenas desenvolvimento tecnológico**.