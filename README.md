🏋️ Model Fitness – Análise de Churn

📊 Descrição do Projeto

A rede de academias Model Fitness está desenvolvendo uma estratégia de relacionamento com clientes baseada em análise de dados.

Um dos principais problemas enfrentados por academias e outros negócios baseados em assinatura é o churn, ou seja, o cancelamento de clientes.

Neste projeto, realizamos uma análise dos dados dos clientes para identificar padrões e fatores que influenciam o churn, permitindo que a empresa desenvolva estratégias mais eficientes para retenção de clientes.

🎯 Objetivo do Projeto

Os principais objetivos desta análise são:

Analisar os dados dos clientes da Model Fitness
Identificar padrões associados ao cancelamento de clientes
Comparar características de clientes que permaneceram e clientes que cancelaram
Gerar insights que possam ajudar a reduzir o churn

📂 Dataset

O conjunto de dados contém informações sobre clientes da academia, incluindo dados demográficos, informações de contrato e comportamento de uso da academia.

Localização do dataset no repositório:

data/gym_churn_us.csv

Principais variáveis presentes no dataset:

gender
Near_Location
Partner
Promo_friends
Phone
Contract_period
Group_visits
Age
Avg_additional_charges_total
Month_to_end_contract
Lifetime
Avg_class_frequency_total
Avg_class_frequency_current_month
Churn

A variável Churn indica se o cliente cancelou ou não a assinatura.

📁 Estrutura do Projeto

Projeto-Model-Fitness
│
├── data
│   └── gym_churn_us.csv
│
├── notebook
│   └── notebook.ipynb
│
└── README.md

Localização do notebook:

notebook/notebook.ipynb
🧪 Metodologia

A análise foi realizada seguindo as seguintes etapas:

Importação das bibliotecas
Carregamento e inspeção inicial dos dados
Pré-processamento dos dados
Análise exploratória de dados (EDA)
Análise estatística do comportamento dos clientes
Visualização dos dados
Identificação de padrões de churn
Conclusões e recomendações de negócio
📈 Principais Insights

A análise revelou alguns padrões importantes relacionados ao churn:

Clientes com baixa frequência de visitas têm maior probabilidade de cancelar o plano.
Contratos mais curtos apresentam maior taxa de cancelamento.
Clientes que participam de aulas em grupo tendem a permanecer por mais tempo.
Clientes com maior tempo de relacionamento com a academia possuem menor probabilidade de churn.

Esses insights podem ajudar a empresa a desenvolver estratégias mais eficazes de retenção de clientes.

🛠 Tecnologias Utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Scikit-learn
Jupyter Notebook
👨‍💻 Autor

Guilherme Marques

Projeto desenvolvido durante o programa de Análise de Dados da TripleTen.

GitHub:
https://github.com/guilhermen29
