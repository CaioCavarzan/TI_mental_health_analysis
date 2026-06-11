#Análise de Saúde Mental em TI

Este repositório contém uma análise de dados focada em entender os fatores que impactam a saúde mental de profissionais da área de tecnologia. O projeto utiliza técnicas de pré-processamento de dados e aprendizado de máquina para identificar as variáveis mais significativas relacionadas ao bem-estar no ambiente corporativo.

##📋 Sobre o Projeto
O objetivo principal deste estudo é realizar uma análise exploratória e preditiva em um dataset de saúde mental (Mental Health in Tech Survey) a fim de prever, dadas as respostas fornecidas pelos entrevistados, se determinado profissional de TI é predisposto a procurar ajuda profissional para questões de saúde mental.

##🛠️ Tecnologias e Ferramentas
O projeto é gerenciado via Poetry, garantindo reprodutibilidade do ambiente:

Linguagem: Python 3.12+
Gerenciamento: Poetry
Manipulação de Dados: Pandas, NumPy
Visualização: Seaborn, Matplotlib
Machine Learning: Scikit-learn
Ambiente de Desenvolvimento: Jupyter Notebook

🚀 Como Executar
Pré-requisitos
Certifique-se de ter o Poetry instalado em sua máquina.

Passos para a reprodução

    1)Clone o repositório:

        Bash
        git clone https://github.com/CaioCavarzan/TI_mental_health_analysis.git cd TI_mental_health_analysis

    2) Instale as dependências:
    O Poetry lerá o arquivo pyproject.toml e instalará exatamente as versões utilizadas durante o desenvolvimento.

        Bash
        poetry install

    3) Inicie o ambiente e o Jupyter:

        Bash
        poetry shell
        jupyter notebook TI_mental_health_analysis.ipynb
