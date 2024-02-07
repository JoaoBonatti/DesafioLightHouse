Título do Projeto

Breve descrição do projeto e seu objetivo.
Conteúdo do Notebook

    1. Introdução
        Breve descrição do contexto do projeto e dos dados utilizados.

    2. Análise Exploratória de Dados (AED)
        Visão geral dos dados.
        Estatísticas descritivas.
        Visualizações (gráficos de barras, histogramas, boxplots, matriz de correlação, etc.).
        Insights e observações importantes obtidos durante a análise exploratória.

    3. Tratamento de Dados
        Limpeza de dados (remoção de duplicatas, tratamento de valores ausentes, correção de valores incorretos, etc.).
        Transformação de dados (normalização, codificação de variáveis categóricas, etc.).
        Engenharia de características (criação de novas características a partir das existentes, seleção de características, etc.).

    4. Treinamento do Modelo
        Escolha do modelo de machine learning adequado para o problema.
        Preparação dos dados para treinamento (separação em conjunto de treinamento e teste, escalonamento, etc.).
        Treinamento do modelo.
        Avaliação do modelo (métricas de desempenho, matriz de confusão, curvas ROC, etc.).
        Ajustes do modelo (otimização de hiperparâmetros, validação cruzada, etc.).

Dependências

Este notebook utiliza as seguintes bibliotecas Python:

    pandas 1.3.3
    numpy 1.21.2
    matplotlib 3.4.3
    plotly 5.3.1
    seaborn 0.11.2
    statistics (incluso na biblioteca padrão do Python)
    pickle (incluso na biblioteca padrão do Python)

Você pode instalar as bibliotecas necessárias utilizando o gerenciador de pacotes pip:

    pip install pandas numpy matplotlib plotly seaborn

Ou também por meio do arquivo requirements.txt disponibilizado no repositório!

    pip install -r requirements.txt

Como Executar

Para executar este notebook localmente, siga as instruções abaixo:

1. Certifique-se de ter Python instalado em seu computador (recomenda-se Python 3.x).
2. Clone ou faça o download do repositório contendo o notebook.
3. Navegue até o diretório onde o notebook está localizado.
4. Crie um ambiente virtual (opcional, mas recomendado):

    python -m venv myenv

4.1. Ative o ambiente virtual:

No Windows:

    myenv\Scripts\activate

No macOS e Linux:

    source myenv/bin/activate

5. Instale as dependências utilizando o gerenciador de pacotes pip:

    pip install -r requirements.txt

6. Certifique-se de que o arquivo requirements.txt contém todas as dependências necessárias.
7. Inicie o notebook Jupyter:

    jupyter notebook

8. No navegador, abra o arquivo do notebook (EDA&MODELO.ipynb) e execute as células conforme necessário.

Autor
João Pedro Bonatti Soares
(48)99103-1394