Identificação de Spoofing em GNSS de Aeronave Utilizando Machine Learning

Este repositório contém o código fonte e a documentação para o projeto de detecção de ataques de Spoofing em receptores GNSS (Global Navigation Satellite System), com foco em Veículos Aéreos Não Tripulados (VANTs/UAVs).

O projeto explora e compara o desempenho de 8 algoritmos de Aprendizado de Máquina (incluindo Deep Learning) para classificar sinais de GPS como autênticos ou falsificados, utilizando um conjunto de dados com 13 características extraídas do receptor.

Autor: Gabriel Borges Pinheiro
Instituição: Instituto Hardware BR

📂 Dataset (Obrigatório)

Para executar este projeto, é necessário realizar o download manual do conjunto de dados, pois ele não está incluído neste repositório devido ao seu tamanho e licença.

Acesse o repositório de dados no Mendeley Data: [https://data.mendeley.com/datasets/z7dj3yyzt8/3](https://data.mendeley.com/datasets/z7dj3yyzt8/3)
(Artigo:"[A DATASET for GPS Spoofing Detection on Unmanned Aerial Systems](https://ieee-dataport.org/documents/dataset-gps-spoofing-detection-autonomous-vehicles)")

Baixe o arquivo específico: GPS_Data_Simplified_2D_Feature_Map.xlsx
Coloque este arquivo no diretório raiz deste projeto (na mesma pasta que o arquivo Codigo.ipynb).

Nota: O código está configurado para ler este arquivo Excel e convertê-lo para CSV para processamento.


🛠️ Tecnologias e Dependências

O projeto foi desenvolvido em Python 3 utilizando Jupyter Notebook. As principais bibliotecas necessárias para execução são:
Manipulação de Dados: pandas, numpy, openpyxl
Visualização: matplotlib, seaborn
Machine Learning: scikit-learn
Balanceamento de Dados: imbalanced-learn (para SMOTE)
Boosting: xgboost
Deep Learning: tensorflow (Keras)

Instalação

Você pode instalar todas as dependências utilizando o pip. Execute o comando abaixo no seu terminal:
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost tensorflow openpyxl


🚀 Como Utilizar

Clone o repositório:

git clone [https://github.com/gabrielbopi/ML_spoofing_detection.git](https://github.com/gabrielbopi/ML_spoofing_detection.git)
cd seu-repositorio


Prepare o Dataset:
Certifique-se de que o arquivo GPS_Data_Simplified_2D_Feature_Map.xlsx (baixado conforme instruções acima) esteja na pasta do projeto.

Execute o Notebook:
Abra o Jupyter Notebook ou JupyterLab:

jupyter notebook Codigo.ipynb
