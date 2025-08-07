Classificação de Câncer de Mama com Machine Learning em R
🎯 Objetivo

Neste projeto, utilizei o conjunto de dados BreastCancer do pacote mlbench para aplicar técnicas de classificação em R. O objetivo foi desenvolver modelos preditivos capazes de distinguir entre tumores benignos e malignos, contribuindo para a detecção precoce do câncer de mama.
🛠️ Tecnologias e Pacotes Utilizados

O projeto foi desenvolvido utilizando a linguagem R, com os seguintes pacotes:

    devtools: Para instalação de pacotes diretamente do GitHub.

    factoextra e FactoMineR: Para análise exploratória e visualização de dados multivariados.

    mlbench: Para acesso ao conjunto de dados BreastCancer.

    corrplot: Para visualização de matrizes de correlação.

    tree: Para construção de árvores de decisão.

    caret: Para treinamento e avaliação de modelos de Machine Learning.

    randomForest: Para implementação do algoritmo Random Forest.

    MASS: Para funções auxiliares em análise estatística.

📊 Conjunto de Dados

O conjunto de dados BreastCancer contém 699 observações com 11 variáveis, sendo 10 preditoras e 1 variável alvo, denominada "Class", que indica se o tumor é benigno ou maligno. Durante o pré-processamento, foram identificados 16 valores ausentes na variável "Bare.nuclei", os quais foram removidos, resultando em 683 observações.
🧹 Pré-processamento dos Dados

    Conversão das variáveis para o tipo numérico.

    Remoção de observações com dados ausentes.

    Análise de correlação entre as variáveis preditoras utilizando a função corrplot().

🌲 Modelos Implementados
1. Árvore de Decisão

    Construção de uma árvore de decisão utilizando a função tree().

    Ajuste do modelo com as variáveis preditoras selecionadas.

    Visualização da árvore gerada.

2. Random Forest

    Treinamento do modelo Random Forest utilizando o pacote randomForest.

    Avaliação do modelo com base na acurácia e importância das variáveis.

📈 Resultados Obtidos

    Árvore de Decisão: A árvore gerada apresentou 10 nós terminais, com uma taxa de erro de classificação de 1,76%.

    Random Forest: O modelo apresentou alta acurácia e identificou as variáveis mais importantes para a classificação.

🧠 Aprendizados e Contribuições

    Pré-processamento de Dados: Aprendi a lidar com dados reais, realizando limpeza e transformação para garantir a qualidade das entradas nos modelos.

    Construção de Modelos: Aprofundei-me na aplicação de algoritmos de classificação, como árvore de decisão e Random Forest.

    Avaliação de Modelos: Utilizei métricas de avaliação para comparar e selecionar os melhores modelos.

    Visualização de Resultados: Utilizei o pacote corrplot para criar gráficos que facilitam a interpretação dos resultados e a comunicação dos achados.

🚀 Como Executar o Projeto

    Clone o repositório:

git clone https://github.com/lanbg/Machine-Learning-R-Classificacao.git

Instale as dependências necessárias:

    install.packages(c("devtools", "factoextra", "FactoMineR", "mlbench", "corrplot", "tree", "caret", "randomForest", "MASS"))

    Carregue o conjunto de dados e execute os modelos conforme os scripts fornecidos.

🌐 Visualização Interativa

Para uma análise interativa e visual dos resultados, acesse o relatório interativo do projeto:

👉 Relatório Interativo - Classificação de Câncer de Mama
📣 Conclusão

Este projeto foi uma oportunidade valiosa para aplicar técnicas de Machine Learning em um problema real de saúde. Ele demonstra minha capacidade de trabalhar com dados reais, desenvolver modelos preditivos e comunicar resultados de forma eficaz. Estou entusiasmado em continuar explorando e contribuindo para a área de Ciência de Dados e Machine Learning.
