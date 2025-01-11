Este projeto aborda o desafio do Titanic do Kaggle, focando em prever quais passageiros sobreviveram ao naufrágio com base em variáveis disponíveis no conjunto de dados. Ele utiliza técnicas de ciência de dados e aprendizado de máquina.

Etapas do Projeto

Importação e Exploração de Dados:Importação de bibliotecas como pandas, numpy, seaborn e matplotlib.
Carregamento dos conjuntos de dados de treino e teste.
Exploração inicial dos dados com visualizações e análises descritivas (info, describe, countplot).

Tratamento de Dados Ausentes:
Identificação de valores ausentes.
Preenchimento de valores nulos para variáveis como Age (usando mediana) e Embarked.

Codificação de Variáveis Categóricas:
Utilização de Label Encoding para a variável Sex (masculino/feminino).
Aplicação de One-Hot Encoding para variáveis como Embarked.

Análise Exploratória:
Visualizações da distribuição da variável alvo (Survived).
Análise da sobrevivência por sexo e classe dos passageiros.

Feature Engineering:
Criação e seleção de variáveis relevantes.
Normalização e padronização de variáveis numéricas (se necessário).

Construção do Modelo:
Desenvolvimento de modelos de aprendizado de máquina utilizando algoritmos como Regressão Logística, Random Forest, ou outros.
Avaliação de desempenho do modelo com métricas como acurácia.

Previsões e Submissão:
Aplicação do modelo ao conjunto de teste.
Geração de arquivo de submissão no formato exigido pelo Kaggle.

Como Executar
Certifique-se de ter o Python instalado com as bibliotecas necessárias: pandas, numpy, matplotlib, seaborn, scikit-learn.
Clone este repositório e abra o notebook.
Execute cada célula sequencialmente para reproduzir os resultados.
