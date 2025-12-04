# Desafio de estatística

### Análise Estatística: Salário de Profissionais de Dados

Este projeto tem como objetivo aplicar técnicas de estatística descritiva em um conjunto de dados contendo informações sobre profissionais da área de dados ao redor do mundo. A ideia é utilizar ferramentas de análise exploratória e visualização para entender como diferentes fatores impactam o salário desses profissionais. 

### Contexto

Você foi contratado para apoiar uma equipe de RH especializada em **tecnologia e ciência de dados**. Essa equipe recebeu uma base de dados com informações salariais de profissionais ao redor do mundo e quer entender **como variáveis como cargo, país, nível de experiência e ano influenciam os salários**.

Sua missão é organizar e explorar os dados, aplicando técnicas de estatística descritiva para extrair **insights relevantes sobre a remuneração #na área de dados**.

### Como começar?

- **Importe os dados** usando a biblioteca `pandas` e explore as primeiras linhas com `.head()`.
- Verifique os tipos de dados, identifique colunas importantes e confira se há valores ausentes.
- Comece com uma análise exploratória simples: frequências, distribuições e estatísticas básicas.
- Use gráficos para visualizar padrões e tendências.

🎯 Etapas de Desenvolvimento

## Etapa 01) Importação e Exploração Inicial da Base

Antes de qualquer análise, é fundamental entender a estrutura dos dados com os quais você está lidando. Nesta etapa, seu foco será **importar o dataset** e realizar uma primeira exploração para verificar:

- Quais colunas estão disponíveis?
- Quantas linhas existem?
- Existem dados ausentes?
- Quais são os tipos de variáveis?


## Etapa 02) **Frequência e Distribuição das Categorias**

Agora que você já conhece a base, vamos explorar as variáveis **categóricas** — aquelas que representam grupos ou classificações, como os **cargos dos profissionais**.

Seu objetivo aqui é responder perguntas como:

- Cargos mais comuns
- Nível de experiência
- Tamanho da empresa

Essas informações ajudam a entender o perfil predominante da base e fornecem contexto para análises salariais futuras.


## **Etapa 03) Estatísticas Descritivas**

A principal variável numérica da base é `salary_in_usd`. Nesta etapa, você vai se aprofundar na análise estatística dessa variável para entender como os salários estão distribuídos.

- **Medidas de tendência central:** média, mediana
- **Medidas de dispersão:** desvio padrão, mínimo e máximo
- **Distribuição geral:** através de histogramas
- **Comparações por grupos:** especialmente por nível de experiência (usando boxplots)


## **Etapa 04)  Comparações por País**

Agora que você já entendeu os salários em geral, é hora de investigar **como eles variam entre diferentes grupos**.

Nesta etapa, seu objetivo será:

- Verificar os **10 países** com as maiores médias salariais

Essas comparações são fundamentais para entender onde estão os maiores salários — seja em termos de função ou localização geográfica.


## **Etapa 05) Correlações e Tendências**

Por fim, vamos analisar se existe alguma relação entre salário e outras variáveis **quantitativas** da base.

As perguntas principais aqui são:

- Existe alguma **tendência de aumento salarial com os anos?**
- Quanto maior o tempo de experiência, maior o salário?

Você irá utilizar uma **matriz de correlação** para investigar essas relações e interpretar os coeficientes gerados.
