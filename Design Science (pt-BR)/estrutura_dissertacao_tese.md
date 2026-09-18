# Estruturando Dissertações e Teses Baseadas em Design Science Research

## Introdução

Uma dissertação ou tese em Design Science Research não segue o mesmo padrão que uma pesquisa experimental tradicional ou um trabalho teórico puro. Enquanto pesquisa experimental estrutura-se tipicamente como "hipótese → método → resultado → conclusão", pesquisa DSR segue a lógica "problema → conhecimento → artefato → avaliação → reflexão → conhecimento de design".

Este capítulo oferece orientação prática sobre como estruturar uma dissertação ou tese em DSR. Fornece não apenas estrutura de seções, mas argumentação esperada em cada seção e traps comuns a evitar.

---

## Estrutura Recomendada para Dissertação de Mestrado em DSR

Uma dissertação de mestrado em DSR tipicamente tem entre 60-100 páginas. Abaixo está uma estrutura recomendada com orientações para cada seção.

### 1. Introdução (4-6 páginas)

A introdução deve rapidamente estabelecer por que sua pesquisa importa e que você compreende o espaço em que está trabalhando.

**Parágrafo de Abertura:** Comece com contexto. Não comece com "Design Science Research é..."; comece com o mundo real. Exemplo: "Organizações de saúde enfrentam desafio crítico de rastrear pacientes de câncer através de múltiplos sistemas heterogêneos. Integração de dados é trabalhosa e propenso a erros, resultando em atraso no tratamento."

**Problema Prático:** Descrição clara e justificada de que é o problema no mundo real que sua pesquisa aborda. Quantifique impacto quando possível. "Em um hospital regional que atende 50,000 pacientes/ano, o tempo médio para integrar dados de um novo paciente é 4 horas, frequentemente com inconsistências."

**Problema Científico:** Articule claramente qual é a lacuna científica que sua pesquisa endereça. Não é suficiente dizer que há "falta de pesquisa". Seja específico. "Enquanto há literatura sobre integração de dados e sobre sistemas de saúde, há lacuna em conhecimento sistemático sobre como desenhar interfaces de integração que equilibrem precisão de dados, velocidade de entrada e usabilidade para profissionais de saúde sob pressão."

**Declaração de Contribuição:** Quem é afetado pelo problema e por que sua pesquisa importa. "Esta pesquisa é relevante para hospitais que implementam sistemas integrados de registros de pacientes, especialmente em contextos de recursos limitados."

**Escopo e Limitações Iniciais:** Dizer brevemente qual é o escopo do seu trabalho. "Esta pesquisa foca em interface de entrada de dados; não aborda segurança de dados ou conformidade regulatória."

**Estrutura da Dissertação:** Breve resumo do que cada capítulo cobrir. Não precisa ser detalhado, apenas orientar o leitor.

**Armadilha Comum:** Muitas introduções gastam 2-3 páginas explicando "o que é Design Science Research" e citando Hevner e Peffers. Isso é desnecessário para um comitê acadêmico que já conhece DSR. Use espaço para estabelecer seu problema específico.

### 2. Revisão de Literatura (12-16 páginas)

A revisão de literatura em DSR serve múltiplos propósitos: (1) demonstrar que você compreende o estado da arte, (2) justificar por que existe lacuna, (3) estabelecer fundações teóricas para seu artefato.

A revisão não é um catálogo de "aqui está o que existe". É uma síntese argumentada que move do geral para o específico.

**Organização Recomendada:**

Comece com um tema amplo relacionado ao seu problema. "Integração de Dados Heterogêneos em Ambientes Organizacionais" é uma seção de alto nível que situa o problema. Descreva abordagens principais: integração em tempo real vs. batch, abordagens orientadas a banco de dados vs. orientadas a serviços, etc. Cite 5-10 trabalhos principais.

Depois, foque em domínio mais específico. "Integração de Dados em Contextos de Saúde" — aqui detalha trabalhos específicos sobre healthcare data integration. O que existe? Que problemas persistem?

Depois, foco ainda mais específico. "Interfaces de Entrada de Dados para Profissionais não-Técnicos" — literatura sobre HCI em ambientes de saúde, sobre design de interfaces para dados criticamente precisos, etc.

Finalize com síntese explícita da lacuna. "Enquanto existe literatura sobre integração de dados [X] e sobre design de interfaces em saúde [Y], há oportunidade de pesquisa em [Z específico]." Aqui você articula exatamente onde sua pesquisa se encaixa.

**Subdivisões Sugeridas:**

- Contexto do Problema (1 seção)
- Soluções e Abordagens Existentes (2-3 seções, cada uma abordando um ângulo diferente)
- Fundamentação Teórica Relevante (1-2 seções — que teorias ou modelos sustentam seu artefato?)
- Lacuna Identificada e Oportunidade de Pesquisa (1 seção)

**Armadilha Comum 1:** Revisão desconectada do problema. Você faz revisão ampla de "Sistemas de Saúde" sem conectar a seu problema específico. Todo parágrafo da revisão deve responder implicitamente: "Por que isto importa para meu problema?"

**Armadilha Comum 2:** Lacuna não articulada. Revisão termina sem dizer claramente "isto é o que não sabemos". Frase final deve ser algo como: "Portanto, há oportunidade de pesquisa em [X específico]."

### 3. Definição do Problema e Objetivos (8-10 páginas)

Esta seção articula de forma precisa o problema que você está resolvendo e os objetivos do seu artefato.

**Problema Detalhado:** Expansão aprofundada do problema introduzido na Introdução. Aqui você fornece dados, contexto, stakeholders específicos. "O hospital X enfrenta o seguinte desafio: 45% das entradas iniciais de pacientes contem erros que requerem correção posterior. Cada erro custa ~$200 em work-up adicional. Impacto anual: ~$450,000."

**Análise de Requisitos:** Como você identificou requisitos? Através de entrevistas? Observação? Análise de dados históricos? "Conduziram-se entrevistas semiestruturadas com 8 profissionais de saúde (enfermeiras, assistentes administrativos) responsáveis por entrada de dados. Análise qualitativa revelou tema recorrente: variação em interpretação de campos resulta em inconsistência."

**Requisitos Especificados:** Lista clara de requisitos que o artefato deve satisfazer. "O sistema deveria: (R1) reduzir erros de entrada em 50%, (R2) manter tempo de entrada por paciente < 15 minutos, (R3) ser operável por profissionais sem treinamento técnico prévio, (R4) integrar com sistema legado de registros."

**Objetivos de Design:** Transformação dos requisitos em objetivos mensuráveis. "Objetivo 1: Reduzir taxa de erros de 45% para < 22%. Métrica: análise de 200 registros de pacientes pré/pós implementação. Objetivo 2: Manter tempo de entrada < 15 min. Métrica: cronometragem de 20 profissionais realizando entrada de 5 pacientes cada."

**Escopo e Limitações:** Clareza sobre o que está incluído e o que está fora de escopo. "Escopo: interface de entrada de dados para admissão inicial. Fora de escopo: integração com laboratório, documentação de diagnóstico, requisições de procedimento."

**Armadilha Comum:** Objetivos vagos. "Melhorar usabilidade" é não-específico. "Aumentar usabilidade conforme medido por SUS (System Usability Scale) de baseline de 52 para > 70" é específico.

### 4. Design e Desenvolvimento do Artefato (14-20 páginas)

Esta é a seção que demonstra que você realmente *desenhou* algo, não apenas implementou.

**Design Iterativo:** Descreva que fez múltiplas iterações. "Prototipagem começou com wireframes em papel, validados com 3 usuários finais através de think-aloud protocol. Feedback levou a redesign de [X], que foi prototipado em HTML, e novamente validado com 5 usuários. Ciclo repetiu 3 vezes até design foi estável."

**Justificação de Decisões de Design:** Cada decisão importante deve ser justificada. Não apenas "implementamos login". "Implementamos single sign-on integrado com active directory da organização porque análise de requisitos mostrou que usuários frequentemente esquecem senhas e cada password reset toma 30 minutos de tempo IT."

**Arquitetura:** Diagrama de alto nível mostrando componentes principais e como se relacionam. Para software: diagrama de camadas. Para método: descrição de fases e artefatos. "Arquitetura consiste de 3 camadas: (1) Camada de Apresentação — interface HTML/CSS focada em entrada estruturada, (2) Camada de Lógica — validação em tempo real de campos, (3) Camada de Persistência — integração com banco de dados legado."

**Tecnologias e Ferramentas:** Descrição de stack técnico. "Frontend em React 18 com TypeScript, validação em tempo real com Zod, backend em Node.js/Express, banco de dados PostgreSQL. Escolhas justificadas por: (1) experiência prévia do time, (2) integração fácil com AD, (3) performance adequada para ~500 requisições simultâneas."

**Processo de Construção:** Não precisa de detalhe excessivo, mas ofereça visibilidade em como trabalho foi estruturado. "Desenvolvimento durou 4 meses. Primeiras 6 semanas em prototipagem e validação com usuários. Semanas 7-14 em implementação full-stack. Últimas 2 semanas em refinamento de performance."

**Código e Artefatos:** Onde está o código? Repositório? Documentação? "Código está em repositório privado [link]. Documentação técnica em [wiki]. Um apêndice fornece schema do banco de dados."

**Desafios e Decisões:** Seja honesto sobre desafios. Que decisões foram difíceis? "Integração com banco de dados legado foi mais complexa que antecipado, porque [razão]. Solução foi [alternativa implementada]."

**Armadilha Comum 1:** Descrição de implementação sem design. "Criamos um form com campos X, Y, Z" descreve implementação. "Baseado em análise de requisitos, decidimos usar form estruturado em vez de interface livre porque usuários precisam de guidance, validação em tempo real reduz erros de entrada significativamente" descreve design.

**Armadilha Comum 2:** Código em vez de design. Não coloque pages de código no documento. Diagrame a arquitetura. Descreva decisões. Refira para repositório se alguém quer ver código.

### 5. Demonstração (3-5 páginas)

Seção breve que mostra que o artefato de fato funciona.

**Cenário de Uso:** Descreva um scenario realista. "Um enfermeiro chega para admitir um novo paciente. Ele navega para URL [X], autentica-se via AD, e é apresentado com form estruturado."

**Screenshots/Diagrama:** Mostre interface. Descreva o que está acontecendo. "Tela mostra [descrição visual]. O campo de data de nascimento implementa date picker para evitar erros de formato."

**Funcionamento End-to-End:** Rastreie uma entrada completa. "Usuário preenche [campos]. Sistema valida em tempo real — [exemplo de validação]. Após submissão, dados são persistidos no banco legado e são visíveis em [outro sistema]."

**Prototipo vs. Produção:** Se demonstração não é com dados reais, seja claro. "Demonstração utiliza dados fictícios similares aos reais. Segurança/privacidade de dados reais não foi comprometida."

**Armadilha Comum:** Demonstração que não é conduzida. "O sistema funciona" sem mostrar como. Use screenshots ou vídeo (se dissertação permite).

### 6. Avaliação (16-22 páginas)

Avaliação é frequentemente a seção que mais distingue pesquisa DSR de desenvolvimento. Seu cuidado aqui demonstra rigor.

**Delineamento Experimental:** Descreva de forma clara a estrutura da avaliação.

"A avaliação foi estruturada em três fases: (1) Avaliação Artificial (Fase 1, semanas 1-2): processamento de 200 registros de pacientes históricos através do sistema, sem intervenção humana, para validar que lógica de validação funciona corretamente. (2) Avaliação Formativa (Fase 2, semanas 3-4): prototipo foi testado com 5 usuários (enfermeiras, assistentes) que realizaram tarefas padrão e forneceram feedback. (3) Avaliação Naturalística (Fase 3, semanas 5-8): sistema foi deployado em produção com 2 enfermarias piloto (~100 admissões/semana) e métricas foram coletadas em operação normal."

**Métricas:** Para cada objetivo de design, descreva como será medido.

"Objetivo 1 (Reduzir taxa de erros de 45% para < 22%): Métrica: taxa de erros calculada como (número de registros com inconsistência detectada durante revisão) / (número total de admissões). Baseline histórico de 45% foi estabelecido através de auditoria de 500 registros de 6 meses pré-sistema. Pós-sistema, mesma metodologia foi aplicada a 500 registros de 4 semanas."

"Objetivo 2 (Manter tempo < 15 min): Métrica: tempo de entrada cronometrado para cada admissão. Método: temporizador automático do sistema, desde login até submissão. 50 admissões foram amostradas aleatoriamente durante semana 1, 3, 6 de operação piloto."

**Participantes:** Quem foi envolvido na avaliação? Como foram selecionados?

"Avaliação formativa envolveu 5 profissionais de saúde: 2 enfermeiras sênior (>5 anos experiência), 2 enfermeiras junior (<2 anos), 1 assistente administrativo. Recrutamento foi voluntário através de anúncio interno. Nenhuma compensação foi oferecida além de reconhecimento do tempo dedicado."

"Avaliação naturalística coletou dados de 2 enfermarias piloto (~40 profissionais totais, ~100 admissões/semana). Participação era obrigatória (sistema foi deployado em ambiente de produção), mas desconforto foi minimizado através de treinamento adequado e suporte."

**Procedimento Detalhado:** Passo-a-passo de como avaliação foi conduzida.

"Fase 1 (Artificial): Pesquisador processou 200 registros históricos usando sistema. Para cada registro, sistema foi avaliado em: (a) validou todos os campos corretamente? (b) rejeitou entrada inválida? (c) aceitou entrada válida? Resultados foram documentados."

"Fase 2 (Formativa): Cada participante foi conduzido através de scenario com 3 admissões fictícias (baixa complexidade, complexidade média, alta complexidade — ex: paciente pediátrico, paciente com múltiplas alergias). Sessão durou ~45 min. Think-aloud protocol foi usado. Sessão foi gravada em áudio. Após tarefa, entrevista semiestruturada de 15 min foi conduzida (O que achou? Que foi difícil? Que sugestões tem?)."

"Fase 3 (Naturalística): Sistema foi deployado. Métricas foram coletadas automaticamente. Semanalmente, reunião de feedback com representantes das enfermarias foi realizada para identificar issues. Após 4 semanas, survey foi distribuído a todos os usuários (10 questões sobre usabilidade, confiança, satisfação)."

**Resultados:** Apresente dados de forma clara e estruturada.

"Fase 1 (Artificial): De 200 registros processados, 198 foram validados corretamente (99% accuracy). 2 registros contem inconsistências menores que não causaram rejeição (ex: formato de telefone ligeiramente não-padrão mas válido). Conclusão: lógica de validação funciona como especificado."

"Fase 2 (Formativa): Tempo médio por cenário: 8.5 min (SD=2.1). Todos os 5 participantes conseguiram completar tarefa. Feedback qualitativo: "Interface é clara, mas [problema 1]", "[Problema 2]", "[Sugestão 1]". Análise de feedback resultou em 3 mudanças de design implementadas."

"Fase 3 (Naturalística): Taxa de erro observada em produção: 21% (95% CI: 18-24%). Isto representa redução de 45% baseline para 21% pós-sistema, excedendo objetivo de < 22% (ainda que marginalmente dentro CI). Tempo médio por admissão: 13.2 min (SD=4.1), dentro do objetivo de < 15 min. Survey (N=38 respondentes): média de 72 em SUS (System Usability Scale), consistente com "bom" usability."

**Análise:** Interprete resultados. O que significam? Há limitações?

"A redução na taxa de erros é significativa e consistente com objetivo de design. Embora não tenhamos redução para < 22% em point estimate (21% está ligeiramente acima), CI inclui 22%, sugerindo que objetivo foi essencialmente atingido. Variação pode ser devida a: (1) efeito novidade (usuários eram mais cuidadosos inicialmente), (2) tipos de erros mudaram (menos erros de formato, mas alguns erros de interpretação permanecem)."

"Limitação notável: Avaliação durou apenas 4 semanas. Seria valioso validar se benefícios persistem após 3-6 meses quando 'novidade' desaparece."

**Armadilha Comum 1:** Ausência de controle/baseline. Você não avalia seu artefato em vácuo. Sempre há comparação: contra sistema anterior, contra padrão da indústria, contra hipótese nula.

**Armadilha Comum 2:** Métricas inadequadas. Escolher o que é fácil de medir, não o que importa. "Número de cliques" é fácil de medir mas talvez irrelevante. "Satisfação de usuário" é difícil de medir bem, mas importa.

**Armadilha Comum 3:** Avaliação apenas artificial. Qualquer sistema funciona bem em laboratório. Avaliação naturalística é crítica.

### 7. Conhecimento de Design e Contribuição Científica (8-12 páginas)

Aqui você extrai conhecimento do trabalho específico para forma transferível.

**Design Principles Identificados:** Articule 3-5 design principles que emergem do seu trabalho.

"Design Principle 1 — Validação em Tempo Real Reduz Erros de Entrada: Em sistemas de entrada de dados críticos, fornecer validação em tempo real (vs. validação apenas ao submit) reduz taxa de erros de entrada em aproximadamente 50%. Evidência: no seu caso, [dados específicos]. Aplicabilidade: contextos similares onde precisão de dados é crítica (saúde, finanças, jurídico)."

"Design Principle 2 — Guidance Estruturada Bate Interface Livre: Para dados complexos ou heterogêneos, uma interface estruturada com campos claros e ordenação lógica bate interface mais livre onde usuário pode entrar dados em qualquer ordem. Evidência: feedback de usuários e análise de erros. Trade-off: interface estruturada é menos flexível se requisitos mudarem."

**Contribuição ao Corpo de Conhecimento:** Como seu trabalho contribui à literatura?

"Esta pesquisa contribui ao corpo de conhecimento em design de sistemas de saúde através de: (1) empirical evidence sobre efetividade de validação em tempo real em reduzir erros em ambiente de saúde específico, (2) framework para elicitação de requisitos em contextos onde usuários final são profissionais de saúde não-técnicos, (3) design principles para interfaces de entrada que balanceiem velocidade e precisão."

**Generalizabilidade:** Seu artefato é específico de um hospital. Mas o conhecimento pode ser mais amplo?

"Enquanto artefato específico (sistema para hospital X) é de uso limitado fora daquele contexto, design principles e insights teóricos são transferíveis para: (1) outros contextos de saúde (clínicas, consultórios), (2) contextos fora de saúde com requisitos similares (entrada de dados críticos em finanças), (3) design de sistemas para usuários não-técnicos em geral."

**Limitações e Trabalho Futuro:** Seja honesto sobre limitações.

"Limitações incluem: (1) Avaliação foi de curta duração (4 semanas). Seria valioso estudar impacto de longo-prazo, incluindo como erros evolem se padrões de entrada de usuários mudam. (2) Hospital específico pode ter características únicas; generalização para outros ambientes de saúde requer validação adicional. (3) Sistema não aborda integração com outros componentes (laboratório, farmácia); impacto end-to-end não foi medido."

"Trabalho futuro poderia: (1) Estender avaliação a múltiplas organizações de saúde, (2) Investigar como training de usuários impacta efetividade ao longo do tempo, (3) Estudar como arquitetura pode escalar a maior número de usuários simultâneos."

**Armadilha Comum:** Reivindicações de impacto infladas. Seu sistema melhorou entrada de dados para 40 profissionais em 1 hospital. Isso é valioso mas não é "revolucionário". Seja preciso sobre escopo de contribuição.

### 8. Conclusão (3-4 páginas)

Síntese breve.

**Reafirmação do Problema:** Remind leitor por que isto importava.

"Esta pesquisa abordou o problema crítico de imprecisão em entrada de dados em ambientes de saúde, onde erros resultam em impacto direto na qualidade de cuidado e custos operacionais."

**Resumo da Solução:** O que você fez?

"Desenvolvemos um sistema de interface de entrada estruturada com validação em tempo real, baseado em análise de requisitos com profissionais de saúde reais. Sistema foi avaliado através de múltiplas fases (artificial, formativa, naturalística) com resultados positivos."

**Contribução:** O que aprendemos?

"O trabalho produz design principles sobre validação em tempo real, guidance estruturada, e design para usuários não-técnicos que são transferíveis além do contexto específico."

**Reflexão Pessoal (Opcional):** Se apropriado, alguma reflexão sobre que foi aprendido pessoalmente através do processo.

"Conduzir esta pesquisa em ambiente de produção real foi desafiador mas supremamente valioso. Teoria em sala de aula é diferente de pragmatismo de contextos reais. Trabalho simultâneo com profissionais de saúde que dependem de seu sistema foi humilhante e reforçou importância de envolver usuários finais cedo e frequentemente."

---

## Estrutura Recomendada para Tese de Doutorado em DSR

Uma tese de doutorado é mais ambiciosa. Tipicamente 100-150+ páginas. Pode explorar múltiplos artefatos, múltiplos contextos, ou aprofundamento teórico.

### Diferenças Principais vs. Mestrado

**Escopo Maior:** Mestrado frequentemente tem 1 artefato em 1 contexto. Doutorado pode ter múltiplos artefatos, múltiplos contextos, ou artefato único com avaliação muito mais aprofundada.

**Contribuição Teórica:** Doutorado é esperado contribuir não apenas com artefato e design principles, mas com entendimento teórico aprofundado. "Por que os design principles funcionam? Qual é a teoria subjacente?"

**Revisão de Literatura Mais Aprofundada:** Tese deveria demonstrar compreensão muito completa do espaço.

**Avaliação Mais Rigorosa:** Avaliação em mestrado pode ser piloto. Em doutorado, deveria ser robusta e de escala.

**Exemplo de Estrutura para Doutorado:**

1. Introdução (6-8 páginas)
2. Revisão de Literatura Sistemática (25-30 páginas) — mais aprofundada que mestrado
3. Fundamentos Teóricos (10-12 páginas) — seção adicional que não é típica em mestrado
4. Primeiro Artefato & Avaliação (25-30 páginas) — prototípico de mestrado inteiro
5. Segundo Artefato & Avaliação (25-30 páginas) — estende trabalho em novo contexto ou com novo design
6. Síntese de Conhecimento de Design (15-20 páginas) — unifica learnings dos múltiplos artefatos
7. Contribuições Teóricas (10-15 páginas) — como seu trabalho avança teoria subjacente
8. Conclusão (5-6 páginas)

### Seção Especial de Doutorado: Contribuições Teóricas

Uma seção que mestrado frequentemente não tem é explicação aprofundada de contribuições teóricas.

"Design principles extraídos deste trabalho sugerem que efetividade de interfaces de dados em ambientes críticos não depende apenas de fatores técnicos (validação) ou de fatores de HCI (clareza visual), mas de **integração coerente entre requisitos de precisão, capacidades cognitivas do usuário, e estrutura da interface**. Teorizando: quando esses três elementos estão alinhados, mesmo com tecnologias simples, resultados são bons. Quando desalinhados (ex: interface clara mas requisitos mal compreendidos, ou usuário compreende mas interface não fornece feedback adequado), resultados são pobres. Isto sugere modelo teórico de 'alignment' que poderia ser testado em outros domínios."

Esta contribuição teórica é que frequentemente distingue doutorado de mestrado.

---

## Armadilhas Comuns em Dissertações/Teses DSR

### Armadilha 1: "Eu construí um software" vs. "Eu pesquisei"

**Sintoma:** Dissertação lê como relatório técnico sobre software desenvolvido. Pouca articulação de problema, de lacuna científica, de design principles.

**Solução:** Pergunta-se constantemente: "O que este trabalho ensina que transcende este software específico?" Se não consegue responder, possivelmente não é pesquisa, é desenvolvimento.

### Armadilha 2: Avaliação Superficial

**Sintoma:** "Desenvolvemos o sistema. Testamos com 5 usuários. Gostaram. Conclusão: sucesso."

**Solução:** Avaliação rigorosa significa: métricas bem definidas, controles/baselines, múltiplas estratégias (artificial + naturalística), análise estatística quando apropriado, discussão de limitações.

### Armadilha 3: Lacuna Científica Não Articulada

**Sintoma:** Literatura review descreve o que existe mas não articula claramente aonde está a oportunidade de pesquisa.

**Solução:** Termine revisão com frase explícita: "Portanto, há oportunidade de pesquisa em [X]." Seja específico. Não "falta pesquisa em sistemas de saúde" mas "falta conhecimento em design de interfaces de entrada para dados críticos que equilibrem precisão, velocidade e usabilidade."

### Armadilha 4: Design Knowledge Não Explicitado

**Sintoma:** Dissertação termina após avaliação. Pouca reflexão sobre o que se aprendeu de forma transferível.

**Solução:** Dedique seção substancial à extração de design principles e insights. Articule quando e por que funcionam, e em que contextos são aplicáveis.

### Armadilha 5: Escopo Infinito

**Sintoma:** "Desenvolvemos um sistema completo de gestão hospitalar". Trabalho nunca termina porque há sempre mais a fazer.

**Solução:** Defina escopo cuidadosamente na seção de Problema & Objetivos. Seja explícito sobre o que está fora de escopo. Melhor ter escopo focado bem executado que escopo amplo superficialmente executado.

### Armadilha 6: Metodologia Não Descrita

**Sintoma:** Seção de Avaliação não descreve claramente delineamento experimental, permitindo leitor questionar rigor.

**Solução:** Delineamento experimental deve ser descrito em detalhe suficiente que alguém poderia replicar. Quantos participantes? Como foram selecionados? Que variáveis foram controladas? Qual foi a sequência exata de eventos?

---

## Checklist para Finalização de Dissertação/Tese DSR

Antes de submeter, responda a estas questões:

- [ ] **Problema:** Está claro qual é o problema prático E qual é a lacuna científica?
- [ ] **Relevância:** Ficou claro por que este problema importa?
- [ ] **Literatura:** Revisão de literatura posiciona seu trabalho no estado da arte?
- [ ] **Requisitos:** Foram elicitados requisitos específicos de verdadeiros stakeholders?
- [ ] **Objetivos:** Objetivos de design são específicos e mensuráveis?
- [ ] **Design:** Decisões de design são justificadas?
- [ ] **Artefato:** Artefato foi de fato construído e demonstrado funcionando?
- [ ] **Avaliação:** Avaliação é rigorosa (não apenas "testamos com usuários e gostaram")?
- [ ] **Métrica:** Cada métrica foi escolhida porque importa, não porque é fácil de medir?
- [ ] **Análise:** Resultados foram analisados com honestidade (não inflados)?
- [ ] **Limitações:** Limitações foram explicitadas?
- [ ] **Design Knowledge:** Design principles foram articulados?
- [ ] **Transferibilidade:** Ficou claro em que contextos design principles são aplicáveis?
- [ ] **Contribuição:** Qual é a contribuição científica além do artefato específico?

Se consegue responder "sim" a todas, possivelmente está pronto.

---

## Estruturação da Escrita

### Tom e Linguagem

Escreva em linguagem clara mas acadêmica. Evite jargão desnecessário. Evite também linguagem casual demais.

**Bom:** "O sistema implementa validação em tempo real, reduzindo taxa de erros de entrada."

**Ruim:** "O sistema é legal porque valida coisas enquanto o cara está digitando."

**Bom:** "Análise qualitativa de feedback de usuários revelou que 4/5 participantes expressaram preocupação sobre [tema]."

**Ruim:** "Usuários não gostaram de [tema]."

### Estrutura de Parágrafo

Um parágrafo bem estruturado tem: (1) Frase tópica que nomeia a ideia principal, (2) Desenvolvimento que fornece detalhe/evidência, (3) Frase de conclusão ou transição que conecta à próxima ideia.

**Exemplo:**

"A avaliação foi estruturada em três fases com objetivo de validar sistema através de estratégias diferentes. Na primeira fase, avaliação artificial foi conduzida através de processamento de dados históricos sem participação de usuários finais, permitindo validação de lógica técnica sem confundimento. Na segunda fase, avaliação formativa envolveu usuários finais em ambiente controlado para obter feedback sobre usabilidade antes de deployment. Finalmente, avaliação naturalística foi conduzida em produção para validar que benefícios observados em laboratório persistem em ambiente real. Essa sequência de fases garantiu que cada aspecto foi testado apropriadamente."

### Uso de Figuras e Tabelas

Figuras e tabelas devem contar uma história. Cada figura deve:
- Ter caption descritivo
- Ser referenciada no texto
- Contribuir significativamente (não apenas decorativa)

**Bom:** Diagrama de arquitetura mostrando componentes e fluxo de dados.

**Ruim:** Screenshot genérica de interface sem contexto.

---

## Recursos Úteis

### Leitura Recomendada

- Hevner et al. (2004) — leitura obrigatória sobre design science research
- Peffers et al. (2007) — metodologia DSRM, referência padrão
- Gregor & Hevner (2013) — posicionamento e contribuição em DSR

### Templates e Ferramentas

- Overleaf (templates de dissertação LaTeX)
- Mendeley (gerenciamento de referências)
- Obsidian ou Notion (nota-taking e organização)

### Grupo de Pesquisa

Se possível, tenha alguém (orientador, colegas) revisando regularmente. Feedback contínuo é valioso.
