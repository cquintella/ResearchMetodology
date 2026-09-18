# Glossário de Termos em Design Science Research

## A

### Avaliação Artificial

Estratégia de avaliação que ocorre em ambientes controlados, frequentemente em laboratório. O pesquisador cria cenários específicos, controla variáveis e mede resultados sob condições predefinidas. Exemplos incluem testes de performance de algoritmos em datasets de teste, testes de usabilidade com participantes em ambiente de laboratório, simulações em ambientes reproduzíveis. A vantagem é precisão e controlabilidade; a limitação é que ambientes reais podem ser significativamente mais complexos e variáveis. Frequentemente usado em fases iniciais de pesquisa ou para componentes específicos que precisam de isolamento.

### Avaliação Formativa

Avaliação que ocorre durante o desenvolvimento do artefato, com objetivo de guiar e melhorar o design. Não busca validar se o artefato alcança objetivos finais, mas fornece feedback que informa iterações de design. Exemplos incluem prototipagem rápida com feedback de usuários, testes de componentes parciais, revisões de desenho com especialistas. Formativa é contínua e orientada ao aprendizado; frequentemente menos formal que avaliação somativa.

### Avaliação Naturalística

Estratégia de avaliação que ocorre em ambientes reais, com usuários ou contextos reais. O pesquisador observa o artefato em uso, coleta dados do ambiente real, mede outcomes que importam na prática. Exemplos incluem teste de software em produção com usuários reais, observação etnográfica de método em uso, análise de impacto de política implementada. A vantagem é autenticidade; a limitação é falta de controle sobre variáveis confundidoras.

### Avaliação Somativa

Avaliação que ocorre ao final do desenvolvimento, com objetivo de demonstrar que o artefato alcança seus objetivos especificados. Busca evidência conclusiva sobre funcionalidade. Somativa é tipicamente mais formal, frequentemente com delineamento experimental cuidadoso, métricas predefinidas. Contrasta com formativa.

---

## C

### Constructo

Conceito ou vocabulário que permite descrever um domínio de forma estruturada. Exemplo: Um framework que organiza tipos de falhas em sistemas distribuídos é um constructo. Uma taxonomia que nomeia e descreve os diferentes estilos arquiteturais é um constructo. Constructos são frequentemente comunicados através de definições, diagramas, modelos conceituais.

### Ciclo de Design

Um dos três ciclos de Hevner. Refere-se ao loop iterativo entre construção refletida de artefatos e avaliação dos mesmos. No ciclo de design, você propõe uma solução, constrói ou protótipa, avalia em contexto controlado, aprende com resultados, refina o design e repete. Ciclos de design tipicamente envolvem múltiplas iterações antes de estar pronto para teste em contextos reais.

### Ciclo de Relevância

Um dos três ciclos de Hevner. Refere-se à conexão contínua entre a pesquisa e o ambiente real. Envolve observação do ambiente, identificação de problemas reais, definição de requisitos com stakeholders, validação de que a pesquisa aborda problemas genuínos. Garante que a pesquisa permanece conectada ao mundo prático.

### Ciclo de Rigor

Um dos três ciclos de Hevner. Refere-se à conexão entre a pesquisa e o corpo de conhecimento existente. Envolve revisão da literatura, compreensão de teor teórico, diálogo crítico com trabalhos relacionados. Garante que a pesquisa não reinventa o já conhecido e contribui rigorosamente ao corpo de conhecimento.

---

## D

### Design Knowledge

Conhecimento que emerge da construção e avaliação de artefatos, articulado em forma transferível. Design knowledge transcende o artefato específico; pode ser aplicado a novos contextos. Exemplos: design principles, design patterns, process guides, diretrizes de trade-off, insights teóricos sobre quando certos designs funcionam. O ponto culminante de uma pesquisa DSR frequentemente é articular claramente que design knowledge foi produzido.

### Design Principle

Diretrização sobre como construir artefatos similares em contextos com características similares. Um design principle bem articulado especifica **quando** é aplicável, **por que** funciona (a base teórica), **que trade-offs** produz, e **em que condições** pode falhar. Exemplo: "Em sistemas de detecção de anomalias onde padrões normais evoluem temporalmente, incorporar mecanismos de retraining periódico e feedback de especialistas melhora significativamente o valor prático do sistema, mas aumenta overhead computacional."

### Design Pattern

Solução recorrente para problema de design específico em contexto particular. Um design pattern nomeia a solução, descreve quando é aplicável, explica como implementar, e discute trade-offs. Exemplo clássico em computação: "o padrão circuit breaker" para lidar com falhas em cascata em sistemas distribuídos. Design patterns são frequentemente documentados com estrutura: nome, contexto, problema, solução, trade-offs.

### DSRM (Design Science Research Methodology)

Framework metodológico proposto por Peffers e colegas que estrutura pesquisa DSR em seis fases: (1) Identificação do problema e motivação, (2) Definição de objetivos da solução, (3) Design e desenvolvimento, (4) Demonstração, (5) Avaliação, (6) Comunicação. Embora apresentado linearmente, na prática as fases são frequentemente iterativas. DSRM é um dos frameworks mais influentes para estruturar pesquisa DSR.

---

## E

### Epistemologia

Ramo da filosofia que investiga como conhecimento é gerado, validado e comunicado. Em Design Science Research, a epistemologia difere da ciência tradicional: não apenas explicamos o que existe, mas investigamos sistematicamente como construir artefatos que resolvem problemas, e que conhecimento emerge dessa construção refletida.

### Escopo do Artefato

Definição clara de quais elementos constituem o artefato versus elementos periféricos. Importante para evitar escopo infinito. Por exemplo, um artefato "sistema de recomendação" tem escopo que inclui algoritmo de recomendação, interface de usuário, e integração com dados; tem escopo que exclui gerenciamento de infraestrutura de TI ou estratégia de marketing.

---

## F

### Framework

Conjunto estruturado de conceitos, componentes e processos que podem ser instanciados em diferentes contextos. Um framework em DSR é um artefato. Exemplo: "Framework para avaliação de maturidade de processos DevOps" que fornece dimensões, métricas, e escalas para avaliar o nível de evolução em diferentes empresas. Diferencia-se de método porque é menos prescritivo; mais oferece uma estrutura dentro da qual adaptações são feitas.

---

## H

### Hevner (Alan Hevner)

Pesquisador influente em Design Science Research, conhecido especialmente pelos "ciclos de Hevner" (relevância, rigor, design) que oferecem perspectiva cíclica sobre pesquisa DSR. Também contribuiu significativamente à definição de rigor em DSR e à compreensão de como articular contribuição científica em pesquisa de design.

---

## I

### Iteração

Processo de repetição cíclica de design, construção e avaliação. Uma "iteração" de um artefato é uma versão produzida durante um ciclo de desenvolvimento. Pesquisa DSR frequentemente envolve múltiplas iterações: você projeta, constrói, avalia, aprende, redesenha baseado no aprendizado, reconstrói. Iteração é central ao aprendizado em DSR.

---

## L

### Lacuna Científica

Aspecto não compreendido, não documentado bem ou não resolvido no conhecimento acadêmico existente. Em Design Science Research, você identifica uma lacuna científica distinta da lacuna prática. Por exemplo, a lacuna prática pode ser "analistas gastam muito tempo revisando alertas falsos"; a lacuna científica é "não temos bem documentados os princípios de design para sistemas de priorização que balanceiem precisão e carga cognitiva". Resolvendo a lacuna científica através de pesquisa, você também resolve a prática.

---

## M

### Métrica

Medida quantitativa ou qualitativa de um atributo. Em avaliação DSR, métricas transformam objetivos em algo mensurável. Exemplo: objetivo "melhorar usabilidade" → métrica "tempo para completar tarefa padrão" ou "score SUS (System Usability Scale)". Métricas devem ser escolhidas cuidadosamente para capturar o que realmente importa, não apenas o que é fácil de medir.

### Método

Processo prescritivo para executar uma classe de tarefas. Um método em DSR é um artefato. Exemplo: "Método para elicitação de requisitos em ambientes ágeis" fornece um passo-a-passo, artefatos intermediários (documentos, planilhas), e critérios de sucesso. Método difere de algoritmo por não ser necessariamente executável por computador; é executável por humanos (frequentemente com ajuda de ferramentas).

---

## P

### Peffers (Ken Peffers)

Pesquisador-chave em Design Science Research, autor primário da DSRM (Design Science Research Methodology), um dos frameworks mais utilizados para estruturar pesquisa DSR. Trabalhos de Peffers continuam referência padrão em como estruturar e comunicar pesquisa em Design Science.

### Princípio de Design

Ver "Design Principle".

### Problema Prático

Aspecto não resolvido no mundo real que causa dificuldade, ineficiência ou sofrimento. Em Design Science Research, você articula claramente qual é o problema prático que sua pesquisa aborda. Exemplo: "Analistas de SOC gastam 80% do tempo revisando false positive alerts, causando fadiga e reduzindo capacidade de detectar ameaças reais". O problema prático deve ser relevante para alguém e ter impacto mensurável.

---

## R

### Reprodutibilidade

Capacidade de alguém externo reproduzir ou replicar sua pesquisa. Pesquisa reproduzível inclui: documentação clara de método, dados disponibilizados (quando possível), código versionado, descrição de decisões. Reprodutibilidade é critério crescente de qualidade em Design Science Research contemporânea, conectada a movimento de ciência aberta.

### Requisito de Design

Característica ou capacidade que o artefato deve ter, derivada do problema e dos objetivos. Requisitos de design frequentemente são derivados de análise do problema, entrevistas com stakeholders, revisão de literatura. Exemplo: "Sistema de detecção deve fornecer explicação de cada alerta em < 100 caracteres, legível para usuários não-técnicos". Requisitos informam decisões de design.

### Relevância

Uma das dimensões de rigor em DSR. Pesquisa DSR é relevante quando aborda problemas genuínos do mundo real e quando resultados têm potencial de impacto prático. Relevância é validada através do ciclo de relevância de Hevner, onde você continuamente conecta com stakeholders reais.

### Rigor

Dimensão de rigor em DSR relacionada a fundamentação em conhecimento acadêmico existente. Pesquisa DSR tem rigor quando baseia-se em teor teórico sólido, em métodos bem estabelecidos, e quando contribui ao corpo de conhecimento científico de forma documentada. Rigor é validado através do ciclo de rigor de Hevner.

---

## S

### Simon, Herbert

Cientista e filósofo (1916-2001) que propôs conceito das "sciences of the artificial" — argumentando que ciência não apenas explica o que existe, mas pode investigar sistematicamente como construir artefatos para atingir objetivos. Trabalho de Simon é fundacional à Design Science Research moderna.

### Stakeholder

Pessoa ou grupo afetado pelo problema que a pesquisa aborda, ou pelo artefato que é desenvolvido. Stakeholders incluem usuários finais, gerentes, especialistas de domínio, pessoas afetadas indiretamente. Envolvimento de stakeholders é crítico em DSR: eles fornecem perspectiva prática, validam que o problema é real, fornecem feedback sobre designs.

---

## T

### Transparência

Característica de pesquisa onde decisões, métodos, dados e razões são documentados e comunicados de forma clara. Pesquisa transparente permite que outros entendam como você chegou aos resultados, avaliem rigorosamente seu trabalho, e eventualmente reproduzam ou construam sobre ele. Transparência é dimensão crescente de qualidade em Design Science Research contemporânea.

### Trade-off

Situação onde melhorar uma dimensão necessariamente envolve sacrificar outra. Exemplos: centralização vs. descentralização de sistemas, latência vs. throughput, precisão vs. recall. Um design principle bem articulado nomeia trade-offs: não apenas descreve quando usar um design, mas reconhece o custo dessa escolha.

---

## V

### Validade

Grau em que resultados de uma avaliação refletem a realidade do que está sendo medido. Há múltiplos tipos: validade interna (as conclusões causais são justificadas?), validade externa (resultados generalizam para outras situações?), validade de construto (a métrica realmente mede o conceito pretendido?), validade ecológica (o ambiente de avaliação é similar ao mundo real?).

### Value-Sensitive Design

Abordagem que incorpora explicitamente considerações sobre valores humanos, éticos, sociais e de sustentabilidade no design de artefatos. Em vez de apenas perguntar "funciona?", pergunta-se "para quem funciona?", "quem é afetado?", "quais valores estão sendo privilegiados?", "como poderia ser abusado?". Movimento crescente em Design Science Research contemporânea.

---

## Z

### (Nenhum termo com Z no contexto DSR padrão)

---

## Notas sobre Uso

Este glossário oferece definições de termos-chave em Design Science Research. As definições buscam ser precisas mas acessíveis. Para definições mais formais ou discussões acadêmicas aprofundadas, consulte as referências principais: Hevner et al. (2004), Peffers et al. (2007), Gregor & Hevner (2013).

Termos frequentemente usados em conjunto (ex: "Ciclo de Relevância" é um dos "Ciclos de Hevner"; "Design Principle" é um tipo de "Design Knowledge") — estas conexões facilitam compreensão integrada de Design Science Research.
