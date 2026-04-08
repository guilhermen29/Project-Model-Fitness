📊 Projeto – Model Fitness (Análise de Churn)

Projeto de Análise de Dados focado na identificação de clientes com risco de cancelamento (churn) em uma rede de academias chamada Model Fitness.

O objetivo do projeto é analisar o comportamento dos clientes, identificar padrões associados ao churn e fornecer insights estratégicos para retenção de clientes.

Este projeto foi desenvolvido utilizando Python para análise de dados, aplicando técnicas de exploração de dados, estatística e visualização.

🎯 Objetivo do Projeto

A academia Model Fitness deseja:

Identificar clientes com maior probabilidade de cancelar o plano
Entender quais fatores influenciam o churn
Criar estratégias de retenção de clientes
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
📂 Dataset

O dataset contém informações sobre clientes da academia, incluindo dados demográficos, comportamento de uso e informações de contrato.

Caminho do arquivo:

data/gym_churn_us.csv

Principais variáveis do dataset:

Variável	Descrição
gender	Gênero do cliente
Near_Location	Cliente mora próximo da academia
Partner	Cliente trabalha em empresa parceira
Promo_friends	Inscrição via indicação de amigos
Phone	Cliente forneceu telefone
Contract_period	Duração do contrato
Group_visits	Participação em aulas em grupo
Age	Idade do cliente
Avg_additional_charges_total	Gastos adicionais
Month_to_end_contract	Meses restantes de contrato
Lifetime	Tempo total como cliente
Avg_class_frequency_total	Frequência média de visitas
Avg_class_frequency_current_month	Frequência no último mês
Churn	Cancelamento do plano (0 = não, 1 = sim)
📓 Notebook de Análise

A análise completa está no notebook:

notebook/notebook.ipynb

Etapas realizadas no notebook:

Importação das bibliotecas
Carregamento do dataset
Análise exploratória de dados (EDA)
Análise estatística dos clientes
Identificação de padrões de churn
Visualização de dados
Conclusões e recomendações de negócio
🛠️ Tecnologias Utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Jupyter Notebook
📈 Exemplos de Análises Realizadas
Distribuição da idade dos clientes
Frequência média de visitas à academia
Comparação entre clientes que cancelaram e que permaneceram
Impacto da duração do contrato no churn
Relação entre frequência de uso e cancelamento
💡 Principais Insights

Alguns padrões observados durante a análise:

Clientes com baixa frequência de visitas apresentam maior probabilidade de churn.
Clientes com contratos mais curtos tendem a cancelar com mais frequência.
Clientes que participam de aulas em grupo têm maior retenção.
Clientes com maior tempo de relacionamento com a academia apresentam menor churn.

Esses insights podem ajudar a academia a criar estratégias de retenção mais eficientes.

🚀 Como Executar o Projeto

1️⃣ Clone o repositório

git clone https://github.com/guilhermen29/Projeto-Model-Fitness.git

2️⃣ Instale as bibliotecas necessárias

pip install pandas numpy matplotlib seaborn scipy

3️⃣ Abra o notebook

notebook/notebook.ipynb
👨‍💻 Autor

Guilherme Marques

Projeto desenvolvido durante o programa de Análise de Dados da TripleTen.

GitHub:
https://github.com/guilhermen29
