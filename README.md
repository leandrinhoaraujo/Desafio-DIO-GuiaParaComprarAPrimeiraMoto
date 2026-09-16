# 🏍️ Guia para Comprar a Primeira Moto

Projeto desenvolvido como parte de um desafio da DIO, utilizando o **NotebookLM** como ferramenta de pesquisa, organização e aprendizagem baseada em fontes.

O objetivo deste projeto é utilizar Inteligência Artificial para auxiliar pessoas que estão passando por uma situação comum: **como escolher a primeira motocicleta?**

---

## 🎯 Objetivo e Contexto

Atualmente estou pesquisando conteúdos para escolher minha primeira motocicleta, principalmente para utilizá-la no trajeto de ida e volta ao trabalho.

Durante essa pesquisa, percebi que existem muitas opções, categorias, cilindradas, características técnicas e formas de aquisição, o que pode tornar a decisão bastante confusa para quem ainda não possui experiência com motocicletas.

Por esse motivo, escolhi desenvolver um Notebook com o tema:

> **Guia para Comprar a Primeira Moto**

O objetivo é criar uma espécie de guia de consulta para pessoas que possuem dúvidas semelhantes, ajudando-as a entender quais fatores devem ser considerados antes da compra e a fazer uma escolha mais adequada às suas necessidades.

A proposta não é simplesmente indicar uma motocicleta, mas **auxiliar o usuário a entender o processo de decisão**, considerando fatores como:

- Perfil de utilização;
- Distância e características do trajeto;
- Experiência do motociclista;
- Altura e peso;
- Tipo de motocicleta;
- Cilindrada e desempenho;
- Conforto e ergonomia;
- Segurança;
- Manutenção;
- Consumo;
- Orçamento disponível;
- Entrada e financiamento;
- Custos envolvidos na aquisição e utilização.

---

# 📚 Curadoria de Fontes

Para construir o NotebookLM, foram utilizadas mais de cinco fontes, incluindo materiais encontrados manualmente e fontes auxiliares obtidas durante o processo de pesquisa.

Entre as fontes selecionadas manualmente, destacam-se:

### 1. YouTube — Conteúdo sobre escolha da primeira moto

https://www.youtube.com/watch?v=AoaLe35_sRQ

Fonte utilizada para obter informações e experiências relacionadas ao processo de escolha de uma primeira motocicleta.

### 2. YouTube — Conteúdo relacionado à compra da primeira moto

https://www.youtube.com/watch?v=-266qRDI4Ak

Utilizada como fonte complementar para identificar diferentes critérios e pontos de atenção durante a escolha.

### 3. Revista Moto.com.br — Guia para iniciantes

https://revista.moto.com.br/acontece/conteudo/como-escolher-a-sua-primeira-moto-guia-completo-para-iniciantes-172189.html

Artigo utilizado como fonte textual para compreender os principais fatores que devem ser considerados por quem está escolhendo sua primeira motocicleta.

> **Observação:** além dessas três fontes apresentadas no README, outras fontes foram adicionadas ao NotebookLM, inclusive com auxílio do recurso de **Deep Research**, para ampliar a base de informações utilizada nas consultas.

---

# 🤖 Engenharia de Prompts

Durante a construção do Notebook, foram realizados testes utilizando diferentes níveis de detalhamento nos prompts.

## 1. Prompts genéricos

Inicialmente foram utilizadas perguntas simples e abertas, como:

- "Qual moto comprar?"
- "Qual moto você sugere?"
- "Qual estilo de moto comprar: scooter, trail ou street?"

Os resultados foram satisfatórios e apresentaram informações úteis, porém as respostas eram relativamente **genéricas**.

Isso aconteceu porque o Notebook não possuía informações suficientes sobre o perfil da pessoa que estava fazendo a pergunta.

Por exemplo, uma recomendação adequada para alguém que percorre poucos quilômetros dentro da cidade pode ser completamente diferente daquela feita para uma pessoa que percorre dezenas de quilômetros diariamente em rodovias.

---

## 2. Prompts personalizados

Depois dos primeiros testes, foi utilizada uma abordagem mais detalhada.

Nesse segundo momento, foram fornecidas informações sobre o usuário, como:

- Idade;
- Altura;
- Peso;
- Experiência com motocicletas;
- Trajeto pretendido;
- Objetivo de utilização;
- Valor disponível para entrada;
- Contexto de utilização.

Um exemplo simplificado da abordagem utilizada foi:

> "Tenho determinada idade, altura e peso, estou começando a pilotar, pretendo utilizar a moto para ir e voltar do trabalho, meu trajeto possui determinadas características e tenho determinado valor disponível para entrada. Com base nas fontes disponíveis, quais categorias e modelos fazem sentido para o meu perfil?"

A diferença foi significativa.

Com mais contexto, o Notebook conseguiu produzir respostas mais específicas, incluindo:

- Sugestões de categorias e motocicletas;
- Características relevantes para o perfil apresentado;
- Pontos positivos e negativos;
- Considerações sobre o trajeto;
- Formas de pagamento;
- Cuidados relacionados a financiamento;
- Aspectos que deveriam ser avaliados antes da compra.

### 📌 Principal aprendizado

Uma pergunta genérica pode gerar uma resposta correta, mas dificilmente será uma resposta realmente personalizada.

**Quanto mais contexto relevante é fornecido, maior é a possibilidade de a IA utilizar as fontes disponíveis de maneira adequada ao problema apresentado.**

---

# 📖 Miniguia de Estudo

Esta seção consolida os principais conhecimentos obtidos durante a pesquisa e utilização do NotebookLM.

## 1. Resumo Estruturado

### 🏍️ 1.1 O que considerar antes de comprar uma primeira moto?

A escolha da primeira motocicleta deve começar pelas **necessidades do motociclista**, e não pelo modelo.

Entre os principais fatores analisados estão:

- Finalidade de uso;
- Distância percorrida;
- Tipo de trajeto;
- Experiência do piloto;
- Ergonomia;
- Categoria da motocicleta;
- Desempenho;
- Segurança;
- Consumo;
- Manutenção;
- Orçamento.

A motocicleta adequada para uma pessoa pode não ser adequada para outra. Por isso, informações sobre o perfil e a utilização são importantes para obter uma análise mais relevante.

---

### 🛵 1.2 Principais categorias

As motocicletas possuem diferentes propostas.

**Scooters** geralmente priorizam praticidade e facilidade de utilização, sendo bastante associadas ao ambiente urbano.

**Street** são motocicletas versáteis e frequentemente utilizadas para deslocamentos urbanos e cotidianos.

**Trail** possuem características voltadas à versatilidade e podem apresentar maior altura e suspensão mais adequada a diferentes tipos de terreno.

A escolha da categoria deve considerar principalmente o tipo de utilização pretendido.

---

### ⚙️ 1.3 Cilindrada, potência e torque

A cilindrada representa o volume deslocado pelo motor, mas **não é suficiente para determinar o desempenho de uma motocicleta**.

Potência e torque também são importantes.

- **Potência:** está relacionada à capacidade do motor de realizar trabalho em determinada taxa.
- **Torque:** representa a força de rotação produzida pelo motor.
- **Cilindrada:** representa o volume deslocado pelo motor.

Duas motocicletas com cilindradas semelhantes podem apresentar desempenhos diferentes devido às características do motor, peso, transmissão e outros fatores.

---

### 🧍 1.4 Ergonomia

A ergonomia é especialmente importante para motociclistas iniciantes.

Devem ser observados fatores como:

- Altura do assento;
- Posição de pilotagem;
- Distância até o guidão;
- Facilidade para apoiar os pés;
- Peso da motocicleta;
- Conforto.

Uma motocicleta pode apresentar boas especificações técnicas e ainda assim não ser adequada ao motociclista devido às características físicas e à posição de pilotagem.

---

### 🛣️ 1.5 O trajeto influencia a escolha

O tipo de trajeto deve ser considerado antes da compra.

Uma motocicleta utilizada predominantemente em trânsito urbano pode ter necessidades diferentes daquela utilizada diariamente em rodovias.

Distância, velocidade, qualidade das vias, trânsito, subidas e necessidade de transportar garupa são exemplos de fatores que podem alterar a escolha.

---

### 💰 1.6 O custo não é apenas o preço da moto

O planejamento financeiro deve considerar o custo total de aquisição e utilização.

Além do preço da motocicleta, podem existir gastos com:

- Entrada;
- Financiamento;
- Juros;
- Seguro;
- Combustível;
- Manutenção;
- Pneus;
- Documentação;
- Equipamentos de proteção.

Por isso, analisar somente o valor da parcela ou o preço anunciado pode fornecer uma visão incompleta do custo real.

---

### 🏦 1.7 Financiamento

Ao analisar uma opção de financiamento, é importante observar não apenas o valor da parcela, mas também:

- Valor de entrada;
- Quantidade de parcelas;
- Taxa de juros;
- Custo Efetivo Total (CET);
- Valor total pago.

Uma parcela que parece acessível individualmente pode representar um custo elevado quando analisada durante todo o período do financiamento.

---

### 🦺 1.8 Segurança

A segurança também deve fazer parte da decisão de compra.

Além das características da motocicleta, devem ser considerados:

- Capacete;
- Equipamentos de proteção;
- Sistemas de frenagem;
- Pneus;
- Iluminação;
- Manutenção preventiva;
- Experiência do motociclista;
- Condições do trajeto.

A escolha da motocicleta deve levar em consideração não apenas desempenho e preço, mas também a capacidade do motociclista de utilizá-la de maneira segura.

---

# 📚 Glossário

| Conceito | Definição |
|---|---|
| **Cilindrada** | Volume total deslocado pelos cilindros do motor. |
| **Potência** | Grandeza relacionada à capacidade do motor de realizar trabalho ao longo do tempo. |
| **Torque** | Força de rotação produzida pelo motor. |
| **ABS** | Sistema que ajuda a evitar o travamento das rodas durante uma frenagem. |
| **CET** | Custo Efetivo Total de uma operação de crédito, considerando os custos envolvidos. |
| **Ergonomia** | Relação entre as características da motocicleta e a posição/conforto do motociclista. |
| **Scooter** | Tipo de motocicleta geralmente associado à praticidade e utilização urbana. |
| **Street** | Categoria de motocicleta geralmente voltada ao uso urbano e cotidiano. |
| **Trail** | Categoria caracterizada por maior versatilidade e, em muitos modelos, maior altura e suspensão de maior curso. |
| **Manutenção preventiva** | Procedimentos realizados periodicamente para preservar o funcionamento e reduzir a possibilidade de falhas. |
| **Financiamento** | Operação de crédito utilizada para adquirir um bem mediante pagamento parcelado. |
| **Entrada** | Valor pago inicialmente na aquisição de um bem financiado. |
| **Custo de manutenção** | Conjunto de gastos necessários para manter a motocicleta em funcionamento adequado. |
| **Relação peso/potência** | Relação entre o peso da motocicleta e sua potência, utilizada como um dos indicadores para analisar desempenho. |

---

# ♻️ Prompts Reutilizáveis

Os seguintes prompts foram desenvolvidos a partir dos testes realizados no NotebookLM e podem ser reutilizados em futuras pesquisas e revisões.

### 🔎 Prompt 1 — Exploração inicial

> **"Com base nas fontes disponíveis, explique quais são os principais fatores que uma pessoa deve considerar ao escolher sua primeira motocicleta. Organize a resposta por categorias e apresente os pontos mais importantes de cada uma."**

**Objetivo:** obter uma visão geral do assunto antes de aprofundar a pesquisa.

---

### 🏍️ Prompt 2 — Comparação de categorias

> **"Compare as categorias scooter, street e trail para uma pessoa que está escolhendo sua primeira motocicleta. Considere utilização urbana, rodoviária, conforto, praticidade, manutenção e desempenho. Explique as características de cada categoria sem escolher uma como universalmente melhor."**

**Objetivo:** entender as diferenças entre categorias e identificar em quais situações cada uma pode ser adequada.

---

### 👤 Prompt 3 — Análise personalizada

> **"Considere o seguinte perfil: idade [IDADE], altura [ALTURA], peso [PESO], experiência [EXPERIÊNCIA], trajeto diário [TRAJETO], finalidade de uso [FINALIDADE] e orçamento/entrada disponível de [VALOR]. Com base exclusivamente nas fontes disponíveis, analise quais características e categorias de motocicletas seriam mais adequadas para esse perfil. Explique o motivo de cada recomendação."**

**Objetivo:** demonstrar como o fornecimento de contexto modifica a qualidade e a especificidade da resposta.

---

### 💰 Prompt 4 — Análise financeira

> **"Estou considerando comprar uma motocicleta no valor de [VALOR]. Tenho [VALOR] para entrada e recebi uma proposta de financiamento de [NÚMERO] parcelas de [VALOR]. Com base nas fontes disponíveis, explique quais informações financeiras devo analisar antes de tomar uma decisão e quais custos adicionais devo considerar."**

**Objetivo:** analisar a compra de forma mais ampla, evitando considerar somente o valor da parcela.

---

### ⚖️ Prompt 5 — Comparação entre modelos

> **"Compare [MODELO A] e [MODELO B] utilizando apenas as informações presentes nas fontes disponíveis. Analise características técnicas, ergonomia, utilização, segurança, manutenção e custos. Separe claramente os dados encontrados nas fontes das informações que não puderem ser confirmadas."**

**Objetivo:** utilizar o Notebook como ferramenta de comparação e, ao mesmo tempo, reduzir respostas baseadas em informações não presentes nas fontes.

---

### 🔍 Prompt 6 — Verificação das fontes

> **"Responda à pergunta utilizando somente as fontes disponíveis no NotebookLM. Para cada informação importante, indique qual fonte sustenta a resposta. Caso as fontes não sejam suficientes para responder, informe explicitamente que não há informação suficiente em vez de fazer uma suposição."**

**Objetivo:** verificar a capacidade do Notebook de fundamentar suas respostas e evitar informações não sustentadas pelas fontes.

---

### 🧠 Prompt 7 — Revisão do conhecimento

> **"Crie 10 perguntas de revisão sobre os principais conceitos aprendidos neste Notebook. Misture perguntas fáceis, intermediárias e difíceis. Não apresente as respostas inicialmente. Depois que eu responder, corrija minhas respostas utilizando as fontes disponíveis."**

**Objetivo:** transformar o Notebook em uma ferramenta de aprendizagem contínua.

---

# 💡 Conclusão do Estudo

A construção deste Notebook demonstrou que a utilização de Inteligência Artificial para pesquisa não depende apenas de fazer perguntas, mas também da **qualidade das fontes, da organização do conhecimento e da forma como os prompts são construídos**.

Os primeiros testes, utilizando perguntas genéricas, produziram respostas úteis, porém amplas. Ao adicionar informações específicas sobre o perfil do usuário e seu objetivo, foi possível obter respostas mais contextualizadas.

Dessa forma, um dos principais aprendizados deste projeto foi entender que **fornecer contexto relevante é fundamental para transformar uma pergunta genérica em uma análise mais útil e personalizada**.

O NotebookLM também pode ser utilizado não apenas para obter respostas, mas como uma ferramenta de estudo, permitindo consultar as fontes, comparar informações, revisar conceitos e criar novas perguntas sobre o assunto.

---

## 🚀 Resultado

O projeto resultou em um NotebookLM estruturado para auxiliar na pesquisa sobre a compra da primeira motocicleta, utilizando fontes selecionadas e diferentes estratégias de prompting.

Além de servir como ferramenta de consulta, o projeto também permitiu experimentar, na prática, como a **curadoria de fontes e a engenharia de prompts influenciam o resultado obtido por uma ferramenta de Inteligência Artificial.**
