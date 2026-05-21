# machine_learn_0408

Este repositório é focado na **Avaliação de Modelos de Classificação**, explorando detalhadamente a **Matriz de Confusão** e as métricas de desempenho derivadas dela, aplicadas ao problema de sobrevivência do Titanic.

## 📂 Conteúdo

* **titanic.csv**: Dataset utilizado para treino e teste do modelo.
* **matriz_de_confusao.ipynb**: Notebook que implementa a lógica de avaliação "do zero". O projeto abrange:
    - **Predição**: Utilização de pesos ($\\beta$) treinados para gerar previsões em dados de teste.
    - **Matriz de Confusão**: Cálculo manual de Verdadeiros Positivos (VP), Verdadeiros Negativos (VN), Falsos Positivos (FP) e Falsos Negativos (FN).
    - **Métricas de Desempenho**: Implementação das fórmulas matemáticas para:
        - **Acurácia**: Proporção de acertos totais.
        - **Precisão**: Qualidade das predições positivas.
        - **Recall (Sensibilidade)**: Capacidade de identificar a classe positiva.
        - **F1-Score**: Média harmônica entre Precisão e Recall.

## 🛠️ Tecnologias e Bibliotecas

As ferramentas centrais utilizadas neste projeto são:

* **Python 3**: Linguagem base.
* **NumPy**: Operações matemáticas para cálculo das métricas.
* **CSV**: Manipulação do dataset.
* **Jupyter Notebook**: Ambiente para execução e apresentação dos resultados.

## 🚀 Como começar

1.  Clone este repositório:
    ```bash
    git clone https://github.com/felipe-r-regiani/machine_learn_0408.git
    ```
2.  Instale o NumPy:
    ```bash
    pip install numpy
    ```
3.  Execute o notebook:
    - Abra o `matriz_de_confusao.ipynb`.
    - Analise a seção de saída para ver a matriz detalhada e como cada métrica reflete o comportamento do modelo frente aos sobreviventes e não-sobreviventes.
