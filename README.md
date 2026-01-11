# Bootcamp de Classificação - Análise Logística

Este projeto é uma análise de dados de uma empresa de logística, desenvolvida como parte de um bootcamp de classificação. O objetivo é construir um pipeline de machine learning para prever resultados logísticos, como atrasos na entrega, com base em diversos atributos operacionais.

## 📈 Pipeline do Projeto

O projeto segue um pipeline de ciência de dados estruturado, dividido nas seguintes etapas:

1.  **Instalação e Importação de Bibliotecas:** Configuração do ambiente com as bibliotecas necessárias.
2.  **Obtenção dos Dados:** Carregamento do dataset `logistica.csv`.
3.  **Análise Exploratória (EDA):** Análise inicial dos dados para entender a distribuição, correlações e características de cada atributo.
4.  **ETL (Extract, Transform, Load):** Limpeza e transformação dos dados, incluindo o tratamento de valores ausentes.
5.  **Pré-processamento:** Preparação dos dados para a modelagem, incluindo normalização e codificação de variáveis categóricas.
6.  **Treinamento e Avaliação:** Treinamento de modelos de machine learning (SVM e Redes Neurais) e avaliação de seu desempenho.

## 💾 Dataset

O dataset utilizado é o `logistica.csv`, que contém as seguintes colunas:

*   **ID_Produto:** Identificador único do produto.
*   **Data_Entrega:** Data prevista para a entrega.
*   **Quantidade_Demandada:** Número de unidades do produto solicitadas.
*   **Estoque_Atual:** Quantidade do produto disponível em estoque.
*   **Recomendacao_Reposicao:** Indicador (Sim/Não) sobre a necessidade de reposição.
*   **Capacidade_Armazem:** Capacidade total do armazém.
*   **Espaco_Disponivel:** Espaço disponível no armazém.
*   **Rota_Entrega:** Rota utilizada para a entrega.
*   **Distancia_km:** Distância da rota em quilômetros.
*   **Tempo_Entrega_horas:** Tempo previsto para a entrega em horas.
*   **Custo_Entrega:** Custo da entrega.
*   **Atraso_Entrega:** Indicador (Verdadeiro/Falso) se houve atraso na entrega.
*   **Desvio_Rota:** Indicador (Verdadeiro/Falso) se houve desvio na rota.

## 🚀 Como Executar o Projeto

Para executar este projeto, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/bootcamp_classificacao_ipog.git
    cd bootcamp_classificacao_ipog
    ```

2.  **Crie um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    ```

3.  **Instale as dependências:**
    Crie um arquivo `requirements.txt` com o seguinte conteúdo:
    ```
    pandas
    numpy
    matplotlib
    seaborn
    scikit-learn
    gdown
    jupyter
    ```
    E instale as bibliotecas:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Inicie o Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

5.  **Abra o notebook:**
    No seu navegador, abra o arquivo `_bootcamp_atividade_classificacao.ipynb`.

6.  **Execute as células:**
    Execute as células do notebook em ordem para reproduzir a análise e o treinamento dos modelos. Certifique-se de que o arquivo `logistica.csv` está no mesmo diretório que o notebook.
