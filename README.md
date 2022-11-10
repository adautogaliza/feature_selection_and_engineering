# Aplicação de Feature Selection e Feature Engineering em Modelos de Classificação e Regressão

O objetivo neste projeto é primordialmente desenvolver modelos de classificação e regressão em um dataset sobre Leads aplicando técnicas de seleção e engenharia de features, procurando melhorar a performance de nossas previsões dentre os modelos desenvolvidos. Para alcançar este objetivo, dividimos o projeto em 3 grandes objetivos:
realizar uma análise explortóra dos dados, construir modelos de clasificação concorrentes e também modelos de regressão distintos.

De maneira geral o objetivo foi:

1º Desenvolver insghts entre as features através da EDA;

2º Contruir modelos preditivos que fossem capaz de informar se um determinado anúncio irá gerar um Lead ou não;

3º Propor a construção de regressores que possam prever a quantidade de leads que um anúncio pode gerar a partir de suas características principais.

Para a construção dos modelos utilizamos:
 - Técnicas de Target Enconding para lidarmos com as features de alta cardinalidade consideradas impróprias para métodos como o OneHotEnconding;
 - Aplicação do método de Mutual Information para selectionar e filtrar features com maior poder preditivo com nosso o target;
 - Criar novas features usando técnicas de clusterização através do algoritmo K-means.
