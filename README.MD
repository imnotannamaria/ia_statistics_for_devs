# Estatística para Devs

## O que é Estatística

Estatística, uma ciência que lida com a **coleta, organização, análise e interpretação de dados**. 

## Sub-áreas da estatística

1. **Probabilidade:** **Estuda a chance de ocorrência de eventos** e ajuda a prever resultados em situações incertas.
2. **Estatística Descritiva:** **Resume e descreve conjuntos de dados** usando medidas como média, mediana e desvio padrão, facilitando a compreensão das características básicas dos dados.
3. **Inferência Estatística:** Permite **tirar conclusões** sobre uma população com base em uma amostra, usando métodos como testes de hipóteses e intervalos de confiança.

## População e Amostra

**População:** Refere-se ao conjunto completo de todas as **entidades individuais que compartilham pelo menos uma característica comum** e são de interesse para o estudo estatístico em questão.

⚠️ **EX:** Considere todos os estudantes de uma escola como a população. Se você estiver interessado em estudar o desempenho acadêmico de todos os alunos matriculados na escola, a população seria o **conjunto completo de todos os alunos da escola**.

**Amostra:** É **uma parte representativa selecionada da população total** que é estudada para fazer inferências ou generalizações sobre a população maior. A amostra é escolhida de forma a representar fielmente as características essenciais da população, tornando possível realizar análises estatísticas significativas sem a necessidade de examinar toda a população.

⚠️ **EX:** Agora, se você selecionar aleatoriamente 100 alunos dessa escola e estudar seus resultados acadêmicos**, essa seleção de 100 alunos representará a amostra**. Com base nessa amostra, você pode fazer inferências sobre o desempenho acadêmico geral de todos os alunos da escola, sem a necessidade de estudar cada aluno individualmente.

### Étapas

1. **População → Amostra:** A população é o grupo total de interesse em um estudo estatístico, enquanto a amostra é uma parte representativa da população que é escolhida para análise.
2. **Análise Descritiva:** Envolve a organização e o resumo dos dados da amostra ou da população, incluindo a identificação de padrões, tendências e características importantes por meio de medidas como média, mediana, moda e desvio padrão.
3. **Informações contidas nos dados:** Refere-se a insights e entendimentos extraídos diretamente dos dados durante a análise descritiva, como a distribuição dos dados, tendências visuais e padrões básicos que podem ser observados inicialmente.
4. **Inferência Estatística:** Utiliza a amostra para fazer inferências ou generalizações sobre a população maior. Isso é feito por meio de testes de hipóteses, intervalos de confiança e outros métodos estatísticos para tirar conclusões baseadas nas características da amostra.
5. **Conclusões sobre as características da população:** Com base nas inferências estatísticas, podemos chegar a conclusões sobre características mais amplas da população, como médias populacionais, proporções ou correlações que são relevantes para o estudo.
6. **Aplicação:** As conclusões obtidas são aplicadas para tomar decisões informadas em vários campos, como ciências sociais, negócios, saúde e muitos outros, contribuindo para o desenvolvimento de políticas, práticas ou estratégias mais eficazes e informadas.

## **Tipos de Variáveis**

1. **Variáveis Quantitativas:** São variáveis **numéricas que representam quantidades mensuráveis**. Elas podem ser de dois tipos:
    
    a. **Intervalo Contínuo (Contínuas):** São variáveis que podem assumir qualquer valor dentro de um intervalo específico. Por exemplo, a **temperatura**, altura, peso ou tempo são exemplos de variáveis contínuas, já que podem ter valores infinitos dentro de um determinado intervalo.
    
    b. **Valores Inteiros (Discretas):** Representam contagens ou números inteiros, e não podem ser subdivididos em valores menores. Exemplos incluem o número de filhos, o **número de carros** em um estacionamento ou o número de pontos marcados em um jogo.
    
2. **Variáveis Qualitativas:** São variáveis que representam atributos ou qualidades que **não podem ser expressos numericamente**. Elas são divididas em dois tipos:
    
    a. **Sem Ordem (Nominais):** São características que não possuem uma ordem natural entre si. Exemplos incluem cores, gênero, **raça** ou tipos de animais.
    
    b. **Com Ordem (Ordinais):** São características que podem ser organizadas ou classificadas com base em alguma ordem específica. Exemplos incluem níveis de educação (primário, secundário, terciário), classificações de **produtos (baixo, médio, alto)** ou escalas de concordância (discordo totalmente, discordo, neutro, concordo, concordo totalmente).
    
    ## **Teorema do Limite Central**
    
    O Teorema do Limite Central é um conceito fundamental na estatística que afirma que, sob certas condições, **a distribuição das médias amostrais de uma população tende a se aproximar de uma distribuição normal, independentemente da forma da distribuição original da população.** Isso é verdade, desde que o tamanho da amostra seja suficientemente grande.
    
    Para ilustrar o Teorema do Limite Central, considere o exemplo de uma população de alturas de todas as pessoas em uma cidade. Se você tirar várias amostras de diferentes tamanhos de indivíduos dessa população e calcular a média de altura em cada amostra, o Teorema do Limite Central afirma que, **à medida que o tamanho das amostras aumenta, a distribuição das médias amostrais se aproximará de uma distribuição normal**, independentemente da forma da distribuição original das alturas na população.
    
    Por exemplo, se a altura das pessoas na população original não segue uma distribuição normal, o Teorema do Limite Central ainda prevê que, com amostras grandes o suficiente, a média das alturas amostradas seguirá uma distribuição normal. Isso permite que os estatísticos façam suposições sobre a distribuição das médias amostrais e usem ferramentas estatísticas que dependem da normalidade, mesmo quando a população original não é normal.
    
    Esse teorema é crucial para muitos aspectos da estatística, como a criação de intervalos de confiança e a realização de testes de hipóteses, tornando possível fazer inferências sobre a população com base em amostras, mesmo quando a distribuição original é desconhecida ou não é normal.
      
    ## Medidas de Posição
    
    - **Média:** É a medida de posição mais comum, obtida pela **soma de todos os valores em um conjunto de dados dividida pelo número de observações**. É sensível a valores extremos, **podendo ser distorcida por valores muito altos ou muito baixos**.
        
        Exemplo: Considere o conjunto de dados {2, 4, 4, 4, 5, 5, 7, 9}. A média seria (2 + 4 + 4 + 4 + 5 + 5 + 7 + 9) / 8 = 40 / 8 = 5.
        
    - **Mediana:** É o valor que **separa a metade superior de uma amostra da metade inferior, quando organizada em ordem crescente ou decrescente. É menos sensível a valores extremos em comparação com a média**.
        
        Exemplo: Considere o conjunto de dados {2, 4, 4, 4, 5, 5, 7, 9}**. A mediana seria 4**, pois está no meio do conjunto quando organizado em ordem crescente.
        
    - **Moda:** É o **valor que aparece com maior frequência** em um conjunto de dados. Pode haver mais de uma moda (bimodal, trimodal, etc.) ou nenhum valor pode se repetir (sem moda).
        
        Exemplo: Considere o conjunto de dados {2, 4, 4, 4, 5, 5, 7, 9}. **A moda seria 4,** pois aparece com mais frequência do que os outros números no conjunto.
