## Repositório usado para anotações e transcrições do Bootcamp Analista de Dados do [IGTI](https://www.igti.com.br/)

# Módulo 1 - Fundamentos


## Capítulo 1 - Conceitos e Fundamentos

### 1.1 Big Data
- O conceito de Big Data segundo o [Grupo Gartner][1]:
    > "São os ativos de informação de *alto volume*, *alta velocidade*
    > e/ou *alta veriedade* que demandam formas de processamento de 
    > informação *inovadoras* e *efetivas em custo* que permitem *insights
    > avançados*, *tomadas de decisão* e *automação de processos*."

- Alto Volume de Dados.
- Alta Velocidade.
- Alta Variedade.

    ![Velocidade-Volume-Variedade][4]

- As informações formam uma base de dados complexa para ser armazenada e processada com ferramentas convencionais.
- Diversidade das fontes de dados.
- Esses dados só fazem sentido se estiverem inseridos em um contexto.
- Nós, seres humanos, estamos sempre contribuindo para o aumento dessa massa de dados.

- Referências: [Cetax][2] - [Wikipedia][3]

#### 1.1.1 Os V's do Big Data

<table>
    <tr>
        <td><b>Nº</b></td>
        <td><b>Características</b></td>
        <td><b>Detalhe</b></td>
        <td><b>Definição</b></td>
    <tr>
    <tr>
        <td>1</td>
        <td> Volume (Volume)</td>
        <td>Tamanho dos Dados</td>
        <td>Quantidade de dados coletados e armazenados</td>
    <tr>
    <tr>
        <td>2</td>
        <td> Velocity (Velocidade)</td>
        <td>Velocidade dos Dados</td>
        <td>A taxa de transferência de dados entre a origem e o destino</td>
    <tr>
    <tr>
        <td>3</td>
        <td>Value (Valor)</td>
        <td>Importância dos Dados </td>
        <td>Representa o valor comercial a ser derivado do Big Data</td>
    <tr>
    <tr>        
        <td>4</td>
        <td>Variety (Variedade)</td>
        <td>Tipo dos Dados</td>
        <td>Tipos diferentes de dados, como fotos, vídeos e áudio, chegam ao final do recebimento</td>
    <tr>
    <tr>
        <td>5</td>
        <td>Veracity (Veracidade)</td>
        <td>Qualidade de Dados</td>
        <td>A análise precisa dos dados capturados é praticamente impossível se os dados não forem verificados</td>
    <tr>
    <tr>
        <td>6</td>
        <td>Validity (Validade)</td>
        <td>Autenticidade dos Dados</td>
        <td>Correção ou precisão dos dados usados ​​para extrair o resultado na forma de informações</td>
    <tr>
    <tr>
        <td>7</td>
        <td>Volatility (Volatilidade)</td>
        <td>Duração de Utilidade</td>
        <td>Volatilidade de big data significa os dados armazenados e por quanto tempo é útil para o usuário</td>
    <tr>
    <tr>
        <td>8</td>
        <td>Visualization (Visualização)</td>
        <td>Apresentação dos Dados</td>
        <td>É essencial que os dados tenha visibilidade, ou seja, sem bem apresentados e disponibilizados</td>
    <tr>
    <tr>
        <td>9</td>
        <td>Virality (Viralidade)</td>
        <td>Velocidade de Espalhamento</td>
        <td> É definida como a taxa na qual os dados são transmitidos / difundidos por um usuário e recebidos por diferentes usuários para uso</td>
    <tr>
    <tr>
        <td>10</td>
        <td>Viscosity (Viscosidade)</td>
        <td>Atraso no Evento</td>
        <td>É uma diferença de tempo que o evento ocorreu e o evento que está sendo descrito</td>
    <tr>
    <tr>
        <td>11</td>
        <td>Variability (Variabilidade)</td>
        <td>Diferenciação dos Dados</td>
        <td>Inconsistência dos Dados, anomalias, outliers além da velocidade inconsistente</td>
    <tr>
    <tr>
        <td>12</td>
        <td>Venue (Local)</td>
        <td>Plataformas Diferentes</td>
        <td>Vários tipos de dados chegaram de diferentes fontes por diferentes plataformas, como sistema pessoal, nuvem pública e privada</td>
    <tr>
    <tr>
        <td>13</td>
        <td>Vocabulary (Vocabulário)</td>
        <td>Terminologia de Dados</td>
        <td>A terminologia de dados, como modelos e estruturas de dados</td>
    <tr>
    <tr>
        <td>14</td>
        <td>Vagueness (Imprecisão)</td>
        <td>Indistinção da Existência de um Dado</td>
        <td>O vago diz respeito à realidade nas informações, sugerindo pouco ou nenhum pensamento sobre o que cada dado pode transmitir</td>
    <tr>
    <tr>
        <td>15</td>
        <td>Verbosity (Verbosidade)</td>
        <td>Redundância de Dados</td>
        <td>A redundância das informações disponíveis em diferentes fontes</td>
    <tr>
    <tr>
        <td>16</td>
        <td>Voluntariness (Voluntariado)</td>
        <td>Disponibilidade dos Dados</td>
        <td>A disponibilidade total de Big Data a ser usada de acordo com o contexto</td>
    <tr>
    <tr>
        <td>17</td>
        <td>Versatility (Versatilidade)</td>
        <td>Flexibilidade dos Dados</td>
        <td>A capacidade do big data de ser flexível o suficiente para ser usado de maneira diferente em diferentes contextos</td>
    <tr>
    <tr>
        <td>18</td>
        <td>Vulnerability (Vulnerabilidade)</td>
        <td>Segurança e Privacidade</td>
        <td>Os dados devem ser disponibilizados e visualizados por diversos grupos, criando a necessidade de um alto controle de acesso aos dados</td>
    <tr>
    <tr>
        <td>
        <td><b>Outras Cacterísticas</b>
        </td>
        </td>
    <tr>
    <tr>
        <td>1</td>
        <td>Complexity (Complexidade)</td>
        <td>Correlação dos Dados</td>
        <td>Os dados são provenientes de diferentes fontes e é necessário descobrir as alterações, sejam pequenas ou grandes, em relação aos dados recebidos anteriormente, para que as informações possam chegar rapidamente</td>
    <tr>
</table>


- Referência: [The 17V's Of Big Data][5]

### 1.2 Machine Learning

#### 1.2.1 Tipos de Aprendizagem

#### 1.2.2 Ajustes do Modelo

#### 1.2.3 Árvores de Decisão

#### 1.2.4 Deep Learning


### 1.3 Data Mining


### 1.4 Data Analytics


### 1.5 Data Science


### 1.6 Bussines Intelligence

#### 1.6.1 OLAP (Online Analytical Processing)

#### 1.6.1 Self Service BI


## Algoritmo K-Means na Prática


## Capítulo 2 - Processos e Técnicas para Análise de Dados


### 2.1 ETL (Extract, Transform and Load)


### 2.2 Armazenamento de Dados

#### 2.2.1 Data Warehouse

#### 2.2.2 Data Mart

#### 2.2.3 Data Lake


### 2.3 Tipos de Análise

#### 2.3.1 Descritiva

#### 2.3.2 Diagnóstica

#### 2.3.3 Preditiva

#### 2.3.4 Prescritiva


### 2.4 Streaming

#### 2.4.1 IoT

#### 2.4.2 CEP


### 2.5 Visualização de Dados

#### 2.5.1 Design Thinking

#### 2.5.2 Data Storytelling


## Prática com Power BI


## Capítulo 3 - Frameworks e Ferramentas


### 3.1 Computação em Nuvem

#### 3.1.1 Modelos de Implantação

#### 3.1.2 Tipologia

#### 3.1.3 Edge Computing


### 3.2 Processamento Paralelo e Distribuído

#### 3.2.1 Apache Kafka

#### 3.2.2 Apache Hadoop

#### 3.2.3 Apache Spark


### 3.3 Banco de Dados Relacionais e Não Relacionais (NoSQL)

### 3.3.1 MongoDB

### 3.3.2 Cassandra

### 3.3.3 Neo4j 

### 3.3.4 Couchbase


## Conhecendo o Couchbase


## Capítulo 4 - Indústria 4.0


### 4.1 Cultura Orientada a Dados

### 4.2 O Cientista de Dados

### 4.3 PIMS (Plant Information Management System)


## Capítulo 5 - Cases Big Data e Data Analytics

### 5.1 Nestré

### 5.2 Netflix

### 5.3 McDonald's

### 5.4 Copa do Mundo

### 5.5 Airbnb

### 5.6 Netshoes

## Referências


[1]:https://www.gartner.com/en/information-technology/glossary/big-data
[2]:https://www.cetax.com.br/blog/big-data/
[3]:https://pt.wikipedia.org/wiki/Big_data
[4]:Apoio/velocidade-volume-variedade.png
[5]:https://www.irjet.net/archives/V4/i9/IRJET-V4I957.pdf
