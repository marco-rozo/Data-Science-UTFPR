# Tópicos em Informática
 
 Aqui vocês irão encontrar os materiais com exemplos de códigos apresentados em sala.



Revisão prova TI26S

- Questões baseadas em concurso
- Só poderá acessar materiais do moodle e git
- Em tratamento e análise de dados
    - tipos de dados (qualitativo e quantitativo)
        - Qualitativos: São tipos de dados que são qualidades, algo que não é numérico
            - Nominal: São dados que não representam hierarquia na qualidade, sem uma distinção de baixo, médio ou alto. Um exemplo disso são cores, podemos ter o azul, vermelho, verde….
            - Ordinal: Também são dados utilizados para categorizar observações, porém nesse caso existe uma hierarquia, níveis de satisfação
        - Quantitativos: São dados que expressam valores numéricos, que podem ser medidos ou contados
            - Discreto: Representam valores inteiros que pode ser contados, por exemplo, pessoas e objetos
            - Contínuo: Representam valores que podem assumir qualquer valor dentro de um intervalo, podendo ser números decimais
- Visualização de dados faltantes: Existem algumas técnicas como
    - Heatmap: Mapa de calor para representação visual que usa cores para indicar a presença ou ausência de valores
    - Gráfico de barras
    - Matriz de Dados faltantes
    - Com o comando data.isnull.sum()
- Métricas básicas, média, desvio padrão, moda, quartis, mediana. São  verificado por variáveis, usando o comando `describe()`
    - Média: A média é a medida de tendência central mais comumente usada. Ela é calculada somando todos os valores em um conjunto de dados e dividindo pela quantidade total de valores. A média é sensível a valores extremos, também conhecidos como outliers.
    - Mediana: A mediana é outro tipo de medida de tendência central. Para calcular a mediana, você deve ordenar os valores em ordem crescente e selecionar o valor central. Se houver um número par de valores, a mediana é a média dos dois valores centrais. A mediana é uma medida robusta que não é afetada por outliers.
    - Moda: A moda é o valor ou valores que aparecem com mais frequência em um conjunto de dados. Um conjunto de dados pode ter uma única moda (unimodal) ou várias modas (multimodal) se houver empates na frequência. A moda é útil em dados categóricos ou dados discretos, mas também pode ser aplicada a dados contínuos.
    - Desvio Padrão: O desvio padrão é uma medida de dispersão que indica o quanto os valores em um conjunto de dados estão afastados da média. Ele mede a variabilidade dos dados. Um desvio padrão alto indica que os valores estão mais dispersos em relação à média, enquanto um desvio padrão baixo indica que os valores estão mais próximos da média, valor a mais ou a menos da média.
    - Quartis: Os quartis dividem um conjunto de dados ordenado em quatro partes iguais. O primeiro quartil (Q1) é o valor que separa os 25% inferiores dos dados. O segundo quartil (Q2) é a mediana, que separa os 50% inferiores dos dados dos 50% superiores. O terceiro quartil (Q3) separa os 75% inferiores dos dados. Os quartis são frequentemente usados para identificar a dispersão dos dados.
        - Os quartis são úteis para entender a distribuição dos dados em um conjunto de dados ordenado. Eles fornecem informações sobre como os dados estão dispersos e como eles se concentram em diferentes partes da distribuição. Aqui estão algumas aplicações dos quartis:
        1. Resumo da Distribuição: Os quartis ajudam a resumir a distribuição dos dados. Eles dividem o conjunto de dados em partes iguais, permitindo identificar como os dados estão espalhados em diferentes regiões. Isso é útil para obter uma visão geral rápida da variação dos dados e sua dispersão.
        2. Identificação de Outliers: Os quartis podem ser usados para identificar valores extremos, também conhecidos como outliers. Valores que estão significativamente acima do terceiro quartil (Q3) ou abaixo do primeiro quartil (Q1) podem ser considerados outliers. Isso pode indicar pontos de dados incomuns ou erros de medição que podem exigir investigação adicional.
        3. Cálculo do Intervalo Interquartil (IQR): O intervalo interquartil é a diferença entre o terceiro quartil (Q3) e o primeiro quartil (Q1). Ele representa a faixa central dos dados, onde a maioria dos valores está concentrada. O IQR é útil para identificar a dispersão dos dados, excluindo a influência de outliers.
        4. Detecção de Assimetria: Os quartis também podem fornecer informações sobre a assimetria da distribuição dos dados. Se o segundo quartil (Q2) (ou mediana) estiver mais próximo do primeiro quartil (Q1), isso indica uma assimetria positiva (cauda direita). Por outro lado, se estiver mais próximo do terceiro quartil (Q3), indica uma assimetria negativa (cauda esquerda).
        5. Análise Comparativa: Comparar os quartis entre diferentes grupos ou subconjuntos de dados pode ajudar a entender como eles diferem em termos de distribuição. Isso é útil para realizar comparações estatísticas e explorar as diferenças entre os grupos.
        
        Em resumo, os quartis fornecem informações importantes sobre a distribuição, variação e dispersão dos dados. Eles ajudam a resumir e descrever a natureza dos dados, permitindo uma análise mais aprofundada.
        
- Definição básica, diferenciação entre eles, saber quando usar cada um de Data Science, Big Data, BI
    - Data Science:
    Data Science é um campo interdisciplinar que envolve a coleta, análise e interpretação de dados para obter insights e conhecimentos. Ele combina elementos de estatística, matemática, programação e conhecimento de domínio para resolver problemas complexos. Os cientistas de dados utilizam técnicas avançadas, como aprendizado de máquina, mineração de dados e visualização, para descobrir padrões, prever tendências e tomar decisões informadas.
    - Big Data:
    Big Data se refere a conjuntos de dados de grande volume, velocidade e variedade, que não podem ser facilmente manipulados e processados com ferramentas tradicionais de gerenciamento de dados. O termo "big data" também engloba os desafios e as tecnologias necessárias para armazenar, processar e analisar esses conjuntos de dados massivos. O foco está em lidar com a escala e complexidade dos dados, bem como extrair valor e insights significativos a partir deles.
    - Business Intelligence (BI):
    Business Intelligence, ou Inteligência de Negócios, refere-se ao processo de coleta, organização, análise e apresentação de informações relevantes para apoiar a tomada de decisões estratégicas em uma organização. O BI envolve a utilização de ferramentas e técnicas para transformar dados brutos em relatórios, painéis e visualizações significativas que ajudam os gestores e as equipes a entender o desempenho do negócio, identificar tendências, detectar problemas e oportunidades, e orientar ações e estratégias.
Diferenças e quando usar cada um:

- Data Science é um campo mais amplo que engloba a análise de dados de várias fontes e setores para descobrir insights e obter conhecimentos. É usado para resolver problemas complexos e realizar análises preditivas e prescritivas em diferentes áreas, desde finanças e marketing até saúde e ciência.
- Big Data refere-se especificamente ao gerenciamento e análise de grandes volumes de dados que são desafiadores para as abordagens tradicionais. É usado quando os dados são muito grandes, rápidos ou variados para serem processados de forma eficiente com técnicas convencionais. É necessário aplicar tecnologias e técnicas específicas para lidar com a escala e a complexidade desses dados.
- Business Intelligence (BI) é um processo de análise e apresentação de informações relevantes para apoiar a tomada de decisões estratégicas em uma organização. O BI é usado para monitorar o desempenho do negócio, fornecer insights operacionais, identificar tendências e padrões de mercado, e fornecer uma base para ações informadas.
- Aprendizagem de máquina, saber diferenciar, algoritmo mais famoso, saber quando utilizar
    - Aprendizado de Máquina, também conhecido como Machine Learning, é uma subárea da Inteligência Artificial que se concentra no desenvolvimento de algoritmos e modelos que permitem que os computadores aprendam e tomem decisões baseadas em dados, sem serem explicitamente programados para realizar tarefas específicas. Vamos explorar a diferenciação, o algoritmo mais famoso e quando utilizar o Aprendizado de Máquina.
        
        Diferenciação:
        Existem diferentes abordagens e tipos de Aprendizado de Máquina, mas podemos destacar duas categorias principais:
        
        - Aprendizado Supervisionado: Nessa abordagem, o algoritmo é treinado em um conjunto de dados rotulados, onde as entradas estão associadas a rótulos ou resultados desejados. O objetivo é aprender uma função que mapeie as entradas para os rótulos corretos, permitindo que o modelo faça previsões ou classificações precisas para novos dados. Exemplos de algoritmos supervisionados incluem regressão linear, regressão logística, árvores de decisão e redes neurais.
        - Aprendizado Não Supervisionado: Nessa abordagem, o algoritmo é exposto apenas a um conjunto de dados não rotulados, sem rótulos ou resultados conhecidos. O objetivo é encontrar estruturas, padrões ou agrupamentos nos dados, sem a necessidade de rótulos. Isso pode ser útil para descobrir insights e segmentações nos dados. Exemplos de algoritmos não supervisionados incluem k-means, análise de componentes principais (PCA) e agrupamento hierárquico.
        - Aprendizado por Reforço: O Aprendizado por Reforço é uma abordagem do Aprendizado de Máquina em que um agente aprende a tomar ações em um ambiente para maximizar as recompensas recebidas. O agente interage com o ambiente, observando seu estado, tomando ações e recebendo feedback na forma de recompensas. O objetivo é aprender uma estratégia (política) que maximize as recompensas ao longo do tempo. É usado em situações em que o ambiente é desconhecido ou complexo, e o agente deve aprender a agir de forma autônoma.
        
        Algoritmo mais famoso:
        Um dos algoritmos mais famosos de Aprendizado de Máquina é o Random Forest (Floresta Aleatória). Trata-se de um algoritmo de aprendizado supervisionado que utiliza um conjunto de árvores de decisão para realizar tarefas como classificação e regressão. Cada árvore é treinada com uma amostra aleatória do conjunto de dados e produz uma previsão. No final, as previsões das árvores são combinadas para obter uma previsão final mais robusta. O Random Forest é conhecido por sua eficácia, capacidade de lidar com grandes conjuntos de dados e resistência ao overfitting.
        
        Quando utilizar o Aprendizado de Máquina:
        O Aprendizado de Máquina é útil em uma ampla gama de situações, especialmente quando:
        
        Os padrões nos dados são complexos e difíceis de serem modelados por meio de regras ou algoritmos tradicionais.
        
        Existe um volume significativo de dados disponíveis para treinar e alimentar os modelos.
        
        A tarefa envolve tomada de decisão, previsão, classificação, agrupamento ou detecção de padrões.
        
        É necessário automatizar tarefas ou processos que normalmente exigiriam uma programação manual extensa.
        
        O ambiente ou as condições mudam com o tempo e é necessário que o modelo seja adaptativo e capaz de aprender com novos dados.
        
        No entanto, é importante lembrar que nem todos os problemas exigem o uso de Aprendizado de Máquina. Às vezes, abordagens mais simples, como regras ou estatísticas descritivas, podem ser suficientes. A escolha do uso do Aprendizado de Máquina depende da natureza do problema, da disponibilidade de dados e do objetivo da análise.
        
- Redução de dimensionalidade, algoritmo principal PCA, objetivo, dado uma tabela com 20 atributos, saber quais atributos são mais relevantes para poder excluir os demais
    - PCA (Principal Component Analysis) é uma técnica que reduz a dimensionalidade dos dados enquanto preserva a maior quantidade possível de informações. Ela encontra combinações lineares das variáveis originais, chamadas de componentes principais, que capturam a maior variância dos dados. O PCA é usado para redução de dimensionalidade, detecção de padrões e pré-processamento de dados em análise de dados e aprendizado de máquina.
- Normalização de dados, dados muito descrepantes, usar o algoritmo escalonador, soma todos os atributos e divide pela média, normalizando ao redor da média
    - A normalização de dados é um processo de ajustar os valores das variáveis em uma escala comum. Isso é feito para lidar com dados muito discrepantes e garantir que as variáveis tenham o mesmo peso durante a análise ou treinamento de modelos de aprendizado de máquina. Algoritmos escalonadores, como o StandardScaler em Python, automatizam esse processo, tornando a normalização mais fácil e eficiente.
- Overfitting e Underfitting, em aprendizagem super visionado, overfitting quando no treino tem muita acurácia e no teste tem resultados ruins, underfitting quando no treino tem resultados ruins e no teste resultados ruins
    - Overfitting ocorre quando um modelo de aprendizado de máquina se ajusta excessivamente aos dados de treinamento, capturando tanto o sinal quanto o ruído nos dados. Isso significa que o modelo se torna muito específico para os dados de treinamento e não generaliza bem para novos dados. Em outras palavras, o modelo "decora" os dados de treinamento, mas não consegue capturar os padrões gerais do problema.
    - Underfitting ocorre quando um modelo de aprendizado de máquina não é capaz de se ajustar bem aos dados de treinamento ou não captura os padrões subjacentes aos dados. O modelo é muito simples para representar adequadamente a complexidade dos dados ou não possui capacidade suficiente para aprender os padrões relevantes. Como resultado, o modelo não consegue fazer previsões precisas tanto nos dados de treinamento quanto nos novos dados.
    
    Em resumo, overfitting ocorre quando um modelo é muito complexo e se ajusta demais aos dados de treinamento, enquanto underfitting ocorre quando um modelo é muito simples e não consegue capturar bem os padrões dos dados. Ambos os casos resultam em desempenho insatisfatório na generalização para novos dados. O objetivo é encontrar um equilíbrio entre o modelo ser suficientemente complexo para capturar os padrões importantes, mas não ser excessivamente complexo ao ponto de se ajustar ao ruído nos dados.
    
- Algoritmos básicos
    - KNN, multiclass
    - Decision Tree, como é montada, o que ela faz, ramificação, dados gerados por meio da entropia, multiclass → mais de duas classes
    - Perceptron, rede neural mais simples, primeira rede neural que surgiu, teve resultados muito bons para casos de classificação binária
    - KNN (K-Nearest Neighbors): É um algoritmo de classificação que se baseia na proximidade dos vizinhos mais próximos para fazer previsões. Ele atribui uma nova amostra à classe mais comum entre seus k vizinhos mais próximos.
    - Decision Tree (Árvore de Decisão): É um algoritmo de aprendizado supervisionado que constrói uma estrutura em forma de árvore, onde cada nó representa uma pergunta sobre os atributos dos dados. A árvore é construída de forma iterativa, dividindo os dados com base em critérios como a entropia, a fim de criar ramos que representem diferentes classes.
    - Perceptron: É uma rede neural artificial simples, composta por um único neurônio. Ele é usado principalmente para problemas de classificação binária, onde busca encontrar um hiperplano que separa as duas classes. O Perceptron atualiza seus pesos com base no erro cometido na classificação das amostras, até que a separação seja alcançada.
    
    Esses são algoritmos básicos que são amplamente utilizados em tarefas de classificação. O KNN se baseia na proximidade dos vizinhos, a Decision Tree constrói uma árvore de decisão para classificar os dados e o Perceptron é uma rede neural simples usada para classificação binária. Cada algoritmo tem suas próprias características e é adequado para diferentes tipos de problemas e conjuntos de dados.
    
- Visualização de outliers, verificando geralmente com boxplots, ficam acima ou abaixo do limite, dados que estão muito fora do restante, dados lixo
    - Outliers são valores atípicos que se diferenciam significativamente dos demais dados em um conjunto. Eles são observações que se encontram longe da maioria dos pontos de dados e podem representar erros de medição, anomalias ou eventos raros. Em resumo, outliers são pontos que se destacam e fogem do padrão geral dos dados.
- Métricas para análise de resultados
    - Matriz de confusão, diagonal principal valores corretos, os outros previsões, valores de confusão. Posso calcular precisão, acurácia, recall (especificidade), F1 Score. Não consigo calcular a curva ROC
    - Análise de correlação dos dados, conseguir verificar quais os dados que estão mais correlacionados com o que, dados mais próximos de 0 não tem correlações, dados mais próximos de 1 muita correlação. Posso ter alta correlação positiva, ou alta correlação negativa, mais próximo de 1 bastante correlacionada, mais próximo de -1 menor correlação
    - Matriz de Confusão: A matriz de confusão é uma tabela que mostra a contagem de previsões corretas e incorretas feitas por um modelo de classificação. Ela compara as previsões do modelo com as classes reais dos dados. A matriz de confusão permite calcular várias métricas, como acurácia, precisão, recall (revocação) e F1-score, que fornecem insights sobre o desempenho do modelo em termos de classificações corretas e incorretas para cada classe.
    - Análise de Correlação dos Dados: A análise de correlação é usada para medir o grau de relacionamento entre duas variáveis em um conjunto de dados. Ela fornece uma medida estatística que indica a força e a direção da relação entre as variáveis. O coeficiente de correlação varia de -1 a 1, onde valores próximos de -1 indicam uma correlação negativa forte, valores próximos de 1 indicam uma correlação positiva forte, e valores próximos de 0 indicam pouca ou nenhuma correlação. A análise de correlação é útil para identificar dependências entre as variáveis e entender como elas se relacionam entre si.
    
    Essas métricas são ferramentas importantes na análise de resultados de modelos de aprendizado de máquina. A matriz de confusão ajuda a avaliar a capacidade do modelo em fazer previsões corretas para cada classe, enquanto a análise de correlação permite identificar associações entre as variáveis do conjunto de dados. Ambas as métricas fornecem informações valiosas para avaliar e interpretar os resultados do modelo.













