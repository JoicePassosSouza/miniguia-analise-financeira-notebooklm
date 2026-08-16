# 📊 Miniguia de Análise Financeira com NotebookLM

## 1. Contexto
Este projeto foi desenvolvido como parte do desafio de aprendizagem ativa com Inteligência Artificial da DIO. O tema escolhido foi análise financeira introdutória, com foco na compreensão de conceitos utilizados para avaliar a situação e o desempenho de um negócio.

O estudo foi desenvolvido utilizando o NotebookLM como ambiente de pesquisa, organização, comparação e revisão das informações presentes nas fontes selecionadas.

## 2. Objetivos de estudo
- Compreender conceitos básicos de análise financeira;
- Diferenciar demonstrações financeiras e seus objetivos;
- Conhecer indicadores financeiros introdutórios;
- Relacionar diferentes indicadores na interpretação de cenários;
- Experimentar diferentes estratégias de prompting;
- Avaliar criticamente respostas produzidas por IA;
- Criar um material reutilizável para futuras revisões.
  
## 3. Curadoria das fontes

As fontes foram selecionadas considerando sua relevância para os conceitos abordados no estudo, a variedade de perspectivas e a disponibilidade de conteúdo aberto para consulta.
  
| # | Fonte | Tipo | Tema principal | Link |
|---|---|---|---|---|
| 1 | MIT Sloan Management Review Brasil | Texto | Fundamentos de finanças | [Acessar fonte](https://mitsloanreview.com.br/financas/) |
| 2 | Escola Superior de Negócios | Texto | Demonstrações financeiras | [Acessar fonte](https://escolasuperioresn.com.br/demonstracoes-financeiras-guia-completo/) |
| 3 | FIA | Texto | Indicadores financeiros | [Acessar fonte](https://fia.com.br/blog/indicadores-financeiros/) |
| 4 | iFinance | Texto | Análise financeira e tomada de decisão | [Acessar fonte](https://www.ifinance.com.br/a-importancia-da-analise-financeira-para-tomada-de-decisoes/) |

## 4. Construção do caderno no NotebookLM
**Tema:** Análise Financeira para Iniciantes
**Ferramenta:** NotebookLM
**Fontes:** 4
**Objetivo:** compreender conceitos financeiros introdutórios e desenvolver um material de revisão.

## 5. Engenharia de Prompts
A etapa de engenharia de prompts teve como objetivo testar diferentes formas de formular perguntas ao NotebookLM e observar como a estrutura das instruções influenciava a qualidade, a clareza e o nível de fundamentação das respostas.

Foram testadas três abordagens, aumentando progressivamente o nível de especificidade, contextualização e orientação para o uso das fontes disponíveis no notebook.

### 5.1 Prompt A
**Objetivo:** 
Compreender os principais conceitos de análise financeira utilizando uma linguagem introdutória.

**Prompt utilizado:**
Com base nas fontes deste notebook, explique os principais conceitos de análise financeira para uma pessoa que está começando a estudar o assunto. Apresente as definições de forma simples e indique a importância de cada conceito para a análise de um negócio.

**Resultado observado:**
O NotebookLM apresentou explicações claras e introdutórias sobre os conceitos financeiros, porém a resposta permaneceu mais geral e teve menor aprofundamento na relação entre os diferentes indicadores.

**Avaliação:**
O prompt foi adequado para uma primeira aproximação com o conteúdo, mas poderia ser mais específico quanto à estrutura esperada da resposta e à necessidade de relacionar os conceitos às fontes.

### 5.2 Prompt B
**Objetivo:** 
Verificar se a apresentação de um cenário prático ajudaria o NotebookLM a relacionar os conceitos financeiros.

**Prompt utilizado:**
Com base nas fontes deste notebook, imagine uma pequena empresa que apresentou aumento de faturamento, mas redução da margem de lucro. Explique de forma simples o que esse cenário pode indicar sobre a situação financeira da empresa e quais informações deveriam ser analisadas para compreender melhor o problema.

**Resultado observado:**
A resposta apresentou uma interpretação do cenário e explicou possíveis relações entre faturamento e margem. Entretanto, apresentou menor nível de detalhamento e fundamentação quando comparada ao terceiro prompt.

**Avaliação:**
A inclusão de um cenário tornou a pergunta mais direcionada, mas ainda havia espaço para especificar quais aspectos deveriam ser analisados e exigir maior rastreabilidade das informações utilizadas.

### 5.3 Prompt C
**Objetivo:** 
Obter uma análise mais completa, contextualizada e fundamentada exclusivamente nas fontes do notebook.

**Prompt utilizado:**
Com base exclusivamente nas fontes deste notebook, analise o seguinte cenário: uma pequena empresa apresentou aumento de receita, redução da margem de lucro e aumento do endividamento. Explique como esses indicadores podem ser interpretados em conjunto, cite as fontes utilizadas e indique quais informações adicionais deveriam ser analisadas antes de chegar a uma conclusão.

**Resultado observado:**
O terceiro prompt produziu a resposta mais completa entre as três experimentações. O NotebookLM conseguiu relacionar os indicadores apresentados no cenário, explicar possíveis interpretações e indicar quais informações adicionais deveriam ser analisadas antes de uma conclusão.

**Avaliação:**
O resultado demonstrou que instruções mais específicas, contextualizadas e orientadas à utilização das fontes tendem a produzir respostas mais completas e úteis para o processo de aprendizagem.

### Evolução dos prompts
A experimentação seguiu uma lógica progressiva:

**Prompt A → Exploração inicial**
- Pergunta ampla;
- Linguagem introdutória;
- Menor direcionamento.


**Prompt B → Contextualização**
- Introdução de um cenário prático;
- Maior direcionamento para interpretação.


**Prompt C → Fundamentação e análise**
- Cenário específico;
- Perguntas delimitadas;
- Solicitação explícita de fontes;
- Necessidade de informações adicionais para conclusão.

## 6. Experimentação e análise dos resultados
A experimentação demonstrou que a forma de elaboração do prompt influencia diretamente a qualidade da resposta obtida.

O Prompt A foi útil para obter uma visão introdutória dos conceitos, mas apresentou uma abordagem mais geral.
O Prompt B trouxe um cenário prático e tornou a análise mais contextualizada, porém a resposta ainda apresentou menor nível de aprofundamento.
O Prompt C apresentou o melhor resultado. Além de fornecer um cenário específico, o prompt determinou exatamente o que deveria ser analisado, solicitou a indicação das fontes utilizadas e pediu que fossem apontadas informações adicionais necessárias antes de uma conclusão.

Dessa forma, o terceiro prompt foi considerado o mais eficiente para o objetivo do estudo, pois combinou contexto, direcionamento, análise crítica e fundamentação nas fontes.

**Principais aprendizados da experimentação:**
- Prompts genéricos tendem a produzir respostas mais amplas e menos aprofundadas;
- A apresentação de um cenário concreto ajuda a contextualizar a análise;
- Especificar exatamente o que deve ser respondido melhora a estrutura da resposta;
- Solicitar fundamentação nas fontes aumenta a rastreabilidade das informações;
- A revisão crítica da resposta é necessária mesmo quando a IA apresenta referências;
- O processo de prompting deve ser tratado como uma etapa iterativa de aprendizagem.

## 7. Troubleshooting / Cicatrizes do processo
Durante a construção do miniguia, algumas respostas do NotebookLM apresentaram simplificações ou interpretações que precisaram ser revisadas.

Entre os principais pontos identificados estavam:

- Obrigatoriedade das demonstrações financeiras: foi necessário corrigir uma generalização que poderia sugerir que todas as empresas possuem exatamente as mesmas obrigações de elaboração e publicação das demonstrações.
- Exemplos hipotéticos: algumas explicações utilizaram exemplos numéricos que não estavam diretamente presentes nas fontes. Para aumentar o nível de fundamentação, os exemplos passaram a ser tratados com maior cautela e vinculados aos parâmetros apresentados no material.
- Ponto de equilíbrio: foi necessário esclarecer que a fórmula apresentada correspondia ao cálculo do faturamento mínimo utilizando a margem de contribuição em percentual.
- EBITDA: foi necessário aprofundar a relação entre o EBITDA e o Lucro Operacional (EBIT), especialmente em relação aos ajustes de depreciação e amortização.

Esses problemas reforçaram um dos principais aprendizados do projeto: a IA deve ser utilizada como ferramenta de apoio ao aprendizado, e não como fonte que deve ser aceita sem questionamento.

## 8. Miniguia de Estudo
O miniguia representa o resultado consolidado do processo de pesquisa, experimentação e revisão realizado no NotebookLM.
Seu objetivo é apresentar os principais conceitos de análise financeira de forma introdutória, organizada e contextualizada.

### 8.1 Conceitos fundamentais
**Finanças**
Finanças estão relacionadas à gestão dos recursos financeiros, envolvendo atividades como planejamento, orçamento, investimento e obtenção de recursos.

**Análise financeira**
A análise financeira utiliza informações das demonstrações financeiras para avaliar a situação e o desempenho de um negócio. Seu objetivo é apoiar decisões, identificar riscos, acompanhar resultados e melhorar a utilização dos recursos.

Por que analisar?
A análise financeira pode auxiliar o gestor a:
- antecipar possíveis problemas;
- identificar desvios em relação aos objetivos;
- avaliar riscos;
- direcionar melhor os recursos;
- apoiar decisões estratégicas.

Uma análise eficiente depende de informações organizadas e atualizadas e pode utilizar comparações entre diferentes períodos para identificar tendências.

### 8.2 Demonstrações financeiras
As demonstrações financeiras organizam informações sobre a situação patrimonial e o desempenho de uma empresa. 

| Demonstração                 | O que apresenta                                           |
| ---------------------------- | --------------------------------------------------------- |
| **Balanço Patrimonial (BP)** | Ativos, Passivos e Patrimônio Líquido em determinada data |
| **DRE**                      | Receitas, deduções, custos, despesas e resultado de um período.      |
| **DFC**                      | Entradas e saídas de caixa                                |
| **DMPL**                     | Alterações no Patrimônio Líquido                          |
| **DVA**                      | Riqueza gerada e sua distribuição                         |

**Balanço Patrimonial**
Pode ser entendido como uma fotografia da situação patrimonial da empresa em determinado momento.

Sua estrutura fundamental é:
*Ativo = Passivo + Patrimônio Líquido*

**DRE**
Pode ser entendida como um filme do desempenho econômico da empresa durante determinado período, permitindo identificar se houve lucro ou prejuízo.

**DFC**
Apresenta a movimentação efetiva de recursos financeiros, permitindo observar a diferença entre o resultado contábil e a disponibilidade de caixa.

**Notas Explicativas**
Complementam as demonstrações financeiras, apresentando informações relevantes sobre critérios contábeis, riscos e outros elementos necessários para interpretar corretamente os números.

### 8.3 Indicadores financeiros
Os indicadores financeiros transformam dados das demonstrações em medidas que facilitam comparações e análises.

**Liquidez Corrente**
Avalia a capacidade de pagamento das obrigações de curto prazo.

**Fórmula:**
*Liquidez Corrente = Ativo Circulante / Passivo Circulante*

Um resultado superior a 1 pode indicar maior equilíbrio financeiro no curto prazo, mas o indicador não deve ser analisado isoladamente.

**ROI**
O Retorno sobre Investimento (ROI) relaciona o retorno obtido ao investimento realizado, permitindo avaliar a eficiência de determinado investimento ou projeto.

**ROE**
O Retorno sobre o Patrimônio Líquido (ROE) relaciona o lucro ao patrimônio dos sócios, permitindo avaliar a capacidade de geração de retorno sobre os recursos próprios.

**Margem de Contribuição**
Representa o valor que sobra das vendas após a dedução dos gastos variáveis, contribuindo para o pagamento dos custos e despesas fixas e posteriormente para a geração de lucro.

Exemplo apresentado nas fontes:

*R$ 20,00 - R$ 10,00 = R$ 10,00*

**Ponto de Equilíbrio Financeiro (PEF)**
Indica o faturamento necessário para que a empresa cubra seus custos e despesas fixas, operando sem lucro ou prejuízo.

**Fórmula:**
PEF = (Custos Fixos + Despesas Fixas) / Margem de Contribuição (%)

> A margem de contribuição deve estar expressa em percentual para que o resultado seja apresentado em valor de faturamento.

**EBITDA**
O EBITDA (LAJIDA) representa o lucro antes de juros, impostos, depreciação e amortização e é utilizado para analisar o desempenho operacional do negócio.

A relação apresentada no estudo é:
*EBITDA = Lucro Operacional (EBIT) + Depreciação + Amortização*

### 8.4 Análise integrada
Um dos principais aprendizados do estudo foi que um indicador isolado não é suficiente para diagnosticar a situação financeira de uma empresa.

Caso: crescimento com redução da margem e aumento do endividamento

Imagine uma empresa que apresenta simultaneamente:
- aumento da receita;
- redução da margem de lucro;
- aumento do endividamento.

À primeira vista, o crescimento da receita pode parecer positivo. Porém, quando analisado em conjunto com a redução da margem e o aumento das dívidas, o cenário pode indicar que a empresa está crescendo sem conseguir preservar sua rentabilidade.

Outro ponto importante é a diferença entre lucro e caixa. Uma venda realizada a prazo pode ser reconhecida contabilmente antes de o dinheiro efetivamente entrar no caixa. Por isso, o crescimento da receita não significa necessariamente crescimento equivalente da disponibilidade financeira.

Por isso, antes de concluir que a empresa está saudável ou em dificuldade, é necessário analisar outras informações, como demonstrações financeiras, fluxo de caixa, indicadores de liquidez, endividamento e rentabilidade.

Principal aprendizado: a análise financeira deve cruzar diferentes informações para transformar números isolados em uma visão mais completa da situação do negócio.

## 9. Glossário
| Conceito                           | Definição resumida                                        | Importância                                                   |
| ---------------------------------- | --------------------------------------------------------- | ------------------------------------------------------------- |
| **Finanças**                       | Gestão dos recursos financeiros                           | Apoiar planejamento e crescimento                             |
| **Análise Financeira**             | Interpretação das informações financeiras                 | Apoiar decisões e avaliar a saúde do negócio                  |
| **Balanço Patrimonial**            | Demonstra a situação patrimonial em determinada data      | Avaliar ativos, passivos e patrimônio                         |
| **DRE**                            | Demonstra o resultado econômico de um período             | Avaliar lucro, prejuízo e rentabilidade                       |
| **DFC**                            | Demonstra entradas e saídas de caixa                      | Avaliar a movimentação financeira                             |
| **Indicadores Financeiros**        | Medidas calculadas a partir de dados financeiros          | Facilitar análises e comparações                              |
| **Liquidez Corrente**              | Relação entre Ativo Circulante e Passivo Circulante       | Avaliar capacidade de pagamento de curto prazo                |
| **EBITDA**                         | Lucro antes de juros, impostos, depreciação e amortização | Avaliar desempenho operacional                                |
| **Custos**                         | Gastos relacionados à atividade-fim                       | Controlar recursos utilizados na operação                     |
| **Despesas**                       | Gastos necessários à estrutura e suporte do negócio       | Controlar gastos administrativos e comerciais                 |
| **Margem de Contribuição**         | Valor das vendas após gastos variáveis                    | Contribuir para cobertura dos gastos fixos e geração de lucro |
| **Ponto de Equilíbrio Financeiro** | Faturamento necessário para cobrir custos e despesas      | Definir o mínimo necessário para não operar com prejuízo      |


## 10. Prompts reutilizáveis
A experimentação realizada durante o projeto permitiu desenvolver um conjunto de prompts que podem ser reutilizados em futuras sessões de estudo.


**Compreender um conceito:**

Com base exclusivamente nas fontes contidas neste notebook, explique o conceito de [CONCEITO FINANCEIRO] para um iniciante. Sua resposta deve ser didática e estruturada em três partes:

1. Uma definição curta, clara e de fácil compreensão;
2. A finalidade prática ou importância deste conceito para a gestão de um negócio;
3. As fórmulas matemáticas, contas contábeis ou componentes associados a ele, se houver.

Não utilize informações externas ao material fornecido e indique as fontes utilizadas.



**Comparar conceitos:**

Faça uma comparação detalhada e didática entre [CONCEITO A] e [CONCEITO B], utilizando exclusivamente as fontes disponíveis neste notebook.

Defina cada conceito, explique suas principais diferenças e demonstre como eles se relacionam na avaliação da saúde financeira de um negócio.

Baseie a comparação nas informações das fontes e indique as referências utilizadas.



**Analisar um cenário financeiro:**

Analise o seguinte cenário financeiro utilizando como base única as fontes disponíveis neste notebook: [DESCREVER CENÁRIO].

Explique como os indicadores podem ser interpretados em conjunto, quais riscos o cenário pode sinalizar e quais demonstrações ou informações adicionais deveriam ser analisadas antes de chegar a uma conclusão.

Fundamente a análise nas fontes do notebook.



**Aplicar um conceito a um exemplo prático:**

Com base exclusivamente nos conceitos e parâmetros descritos nas fontes deste notebook, crie um exemplo prático e simplificado para ilustrar a aplicação de [CONCEITO FINANCEIRO].

Apresente um cenário de pequena empresa, valores numéricos simples, o passo a passo dos cálculos e indique quais fontes fundamentaram a lógica utilizada.



**Revisar o conteúdo aprendido:**

Crie um minirroteiro de revisão sobre os seguintes conceitos: [LISTAR CONCEITOS].

Utilize apenas o conteúdo disponível no notebook. Apresente uma síntese de cada conceito, explique sua aplicação na tomada de decisão e proponha três perguntas de revisão acompanhadas das respectivas respostas esperadas.



**Avaliar criticamente uma resposta:**

Atue como um revisor técnico rigoroso. Avalie criticamente a seguinte resposta ou afirmação:

[INSERIR TEXTO]

Compare a afirmação com o conteúdo das fontes deste notebook e identifique:

1. Generalizações que possam induzir a erro;
2. Simplificações conceituais inadequadas ou imprecisões técnicas;
3. Informações que não estejam amparadas pelas fontes.

Para cada problema identificado, explique o motivo da inconsistência e sugira uma correção fundamentada nas fontes.

## 11. Reflexão final
A utilização do NotebookLM permitiu transformar diferentes fontes de informação em um ambiente estruturado de estudo. Durante o processo, foi possível perceber que a qualidade das respostas não depende apenas das fontes utilizadas, mas também da forma como as perguntas e instruções são formuladas.

A experimentação com diferentes prompts mostrou que instruções mais específicas, contextualizadas e fundamentadas nas fontes produziram respostas mais completas e confiáveis. A revisão crítica também foi importante para identificar generalizações e simplificações inadequadas, demonstrando a necessidade de avaliar as respostas da IA em vez de aceitá-las automaticamente.

O processo também mostrou que a utilização da IA para aprendizagem não deve ser limitada à obtenção de respostas prontas. Ao questionar, comparar, revisar e reformular as instruções, o estudante participa ativamente da construção do conhecimento.

Ao final, o NotebookLM funcionou não apenas como uma ferramenta de resumo, mas como um apoio para pesquisa, comparação de informações, revisão de conceitos e organização do conhecimento. O processo também resultou em prompts reutilizáveis que podem apoiar futuros estudos e revisões sobre temas financeiros.

## 12. Conclusão
O projeto possibilitou explorar a Inteligência Artificial como uma ferramenta de aprendizagem ativa, combinando curadoria de fontes, engenharia de prompts, pensamento crítico e organização do conhecimento.

A principal conclusão obtida foi que a qualidade da interação com a IA depende tanto da qualidade das fontes quanto da qualidade das instruções fornecidas e da capacidade do usuário de avaliar criticamente os resultados.

A partir das quatro fontes selecionadas, foi possível construir um miniguia introdutório sobre análise financeira, organizar um glossário de conceitos fundamentais e desenvolver prompts reutilizáveis para futuras sessões de estudo.

Dessa forma, o projeto não resultou apenas em um material sobre análise financeira, mas também em um processo de aprendizagem sobre como utilizar IA de maneira mais consciente, crítica e estratégica.
