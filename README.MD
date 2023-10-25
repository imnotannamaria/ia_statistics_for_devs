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

## Medidas de Dispersão

1. **Variância:** A variância é uma medida da dispersão dos dados em relação à média. **Ela mede o quão distantes os valores estão da média**. Uma variância alta indica que os valores estão amplamente espalhados em torno da média.
    
    Exemplo: Considere o conjunto de dados {2, 4, 4, 4, 5, 5, 7, 9}. A variância seria calculada como a **média dos quadrados das diferenças entre cada valor e a média**, resultando em um valor numérico que representa a dispersão dos dados.
    
2. **Desvio Padrão:** O desvio padrão é a medida mais comum da dispersão dos dados em relação à média. **É a raiz quadrada da variância** e é expresso na mesma unidade que os dados originais.
    
    Exemplo: Usando o mesmo conjunto de dados {2, 4, 4, 4, 5, 5, 7, 9}, **a variância seria calculada primeiro e, em seguida, o desvio padrão seria a raiz quadrada desse valor**.
    
3. **Coeficiente de Variação:** O coeficiente de variação (CV) é uma medida relativa da dispersão dos dados em relação à média, expressa como uma porcentagem. Ele permite comparar a dispersão entre diferentes conjuntos de dados que possam ter médias muito diferentes.

Exemplo: Se você tiver dois conjuntos de dados com médias e desvios padrão diferentes, o CV permitirá determinar qual conjunto de dados tem uma variação relativa mais alta ou baixa em relação à média.

## Medidas de forma

### **Assimetria**

Refere-se à **falta de simetria em uma distribuição**. Uma distribuição simétrica terá valores idênticos à esquerda e à direita da média, enquanto uma distribuição assimétrica **terá uma cauda mais longa em um dos lados da média**.

**EX**: Considere um conjunto de dados que representa os lucros trimestrais de uma empresa. Se a maioria dos lucros estiverem concentrados nos quartos finais do ano, isso resultará em uma assimetria positiva. Se a maioria dos lucros estiver nos quartos iniciais, teremos uma assimetria negativa.

### Tipos

- Simétrica
- Assimétrica à Direita (Positiva)
- Assimétrica à Esquerda (Negativa)

### **Curtose**

A curtose mede o **pico ou a "apontamento" de uma distribuição**, ou seja, quão afilada ou achatada é em comparação com uma distribuição normal. Uma curtose alta indica uma distribuição mais concentrada em torno da média, com caudas mais pesadas, enquanto uma curtose baixa indica uma distribuição mais achatada.

**EX**: Considere um conjunto de dados que representa a distribuição de alturas de árvores em uma floresta. Se a distribuição for mais concentrada em torno de um valor central com caudas mais pesadas, ela terá uma curtose alta. Se a distribuição for mais plana e espalhada, terá uma curtose baixa.

### Tipos

- **Mesocúrticas**: A própria **curva normal** padrão
- **Platicúrtica**: Possui grau de **achatamento maior** que da curva normal padrão, o que nos indica que os dados estão mais espalhados (logo, o desvio padrão também é maior)
- **Leptocúrtica**: Seu grau de **achatamento é menor** que o da curva normal padrão (curva mais pontiaguda), indica que os dados estão concentrados (desvio padrão menor)

## Correlação

### **Associação Positiva**

Associação positiva ocorre quando duas variáveis **têm uma relação na qual, à medida que uma variável aumenta, a outra também aumenta**. Em outras palavras, quando uma variável cresce, a outra tende a crescer na mesma direção.

**Exemplo:** Considere um estudo que analisa a relação entre o tempo de estudo de um estudante e suas notas em um exame. Se à medida que o tempo de estudo aumenta, as notas do exame também aumentam, isso representa uma associação positiva. Quanto mais tempo o aluno estuda, melhores são suas notas.

### **Associação Negativa**

Associação negativa ocorre quando duas variáveis têm uma relação na qual, **à medida que uma variável aumenta, a outra diminui.** Em outras palavras, quando uma variável cresce, a outra tende a diminuir na mesma direção.

**Exemplo:** Suponha que você esteja investigando a relação entre a quantidade de exercício físico que as pessoas fazem e seu peso corporal. Se, à medida que a quantidade de exercício aumenta, o peso corporal diminui, isso indica uma associação negativa. Quanto mais alguém se exercita, menor é o seu peso.

### **Sem Associação**

A ausência de associação ocorre quando **não há uma relação clara ou sistemática entre duas variáveis.** Nesse caso, as mudanças em uma variável não afetam consistentemente a outra variável.

**Exemplo:** Se você examina a relação entre a quantidade de gelo consumida por pessoas e o número de pássaros em um determinado local, pode não haver uma associação significativa. A quantidade de gelo consumida não terá um impacto direto no número de pássaros na região, portanto, não haverá associação clara entre essas duas variáveis.

### Coeficiente de Pearson

O coeficiente de Pearson é uma medida de correlação usada para avaliar a **relação linear entre duas variáveis contínuas**. Ele mede a força e a direção da relação entre as duas variáveis. Seu valor varia de -1 a 1, onde 1 indica uma correlação positiva perfeita, 0 indica ausência de correlação e **-1 indica uma correlação negativa perfeita**.

**Exemplo de Coeficiente de Pearson:** Considere um estudo que analisa a relação entre as horas de estudo e o desempenho dos alunos em um exame. Se o coeficiente de Pearson for calculado como 0,8, isso indica uma correlação positiva forte, sugerindo que mais horas de estudo estão positivamente relacionadas a um melhor desempenho no exame.

📢 OBS: Adequado para variáveis numéricas que possam ter uma relação linear

### Coeficiente de Spearman

O coeficiente de Spearman é uma medida de correlação usada para **avaliar a relação entre duas variáveis, independentemente de serem contínuas ou ordinais**. Ele avalia a monotonicidade, ou seja, a consistência na direção das mudanças entre as duas variáveis.

**Exemplo:** Considere um estudo que analisa a relação entre a classificação dos alunos em dois exames diferentes. Se o coeficiente de Spearman for calculado como 0,7, isso indica uma correlação positiva forte entre as classificações dos alunos nos dois exames, o que sugere que os alunos que se saem bem em um exame também tendem a se sair bem no outro.

📢 OBS: Adequado quando dos dados não tem uma relação linear clara ou quando as variáveis não são numericamente escalonáveis.

## Representação gráfica

### Histograma

- É usado para variáveis numéricas contínuas, mostrando a distribuição doa dados em intervalos.

### Barras

- Aplicável a variáveis categóricas ou discretas, exibindo a contagem ou frequência de cada categoria.

### Dispersão

- Usado para mostrar a relação entre duas variáveis numéricas, ajudando a identificar padrões ou tendências.

### Box Plot

- Adequado para variáveis numéricas ou categóricas ordinais, revelando distribuição, mediana e valores atípicos. 

### Linhas

- Utilizado para variáveis numéricas ao longo do tempo ou em uma sequência, destacando tendências temporais.