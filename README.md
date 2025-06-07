# 📈 Projeto de Análise de Churn – Telecom X

Este projeto tem como objetivo identificar padrões de evasão (churn) de clientes da empresa **Telecom X**, utilizando dados reais para auxiliar em estratégias de **retenção de clientes**. A análise foi conduzida utilizando Python e bibliotecas de ciência de dados.

🔗 [Repositório no GitHub](https://github.com/TheGabrielVieira/challenge2-data-science)

---

## 🔍 Sobre o Projeto

A evasão de clientes é um desafio comum no setor de telecomunicações. Através de uma análise detalhada dos dados, buscamos entender os fatores que levam os clientes a cancelar seus serviços.

### 🎯 Objetivo
- Analisar o perfil dos clientes que cancelam os serviços.
- Identificar padrões e correlações que indiquem maior risco de churn.
- Gerar insights acionáveis para retenção.

---

## 📂 Etapas Realizadas

1. **Coleta e Pré-processamento dos Dados**
   - Extração de dados em formato JSON.
   - Conversão para DataFrame Pandas.
   - Tratamento de valores ausentes e inconsistências.

2. **Limpeza e Transformação**
   - Conversão de tipos de dados.
   - Normalização de variáveis categóricas.
   - Criação de variáveis auxiliares (`Daily_Charges`, etc.).

3. **Análise Exploratória de Dados (EDA)**
   - Visualizações com Seaborn e Matplotlib.
   - Análises univariadas, bivariadas e multivariadas.
   - Cálculo de estatísticas descritivas e mapa de correlação.

4. **Geração de Relatório**
   - Consolidação dos resultados, insights e recomendações estratégicas.

---

## 📊 Principais Insights

- **Contratos mensais** têm a maior taxa de evasão.
- Clientes com **menor tempo de contrato** tendem a sair mais.
- **Internet via fibra** está associada a maior churn.
- **Serviços adicionais** como segurança e backup estão ligados à maior permanência.
- Métodos de pagamento **automáticos** apresentaram maior evasão.

---

## 🧠 Conclusões e Recomendações

- Incentivar **contratos mais longos** com benefícios.
- Monitorar e melhorar a **qualidade da internet de fibra**.
- Criar campanhas para promover **serviços adicionais**.
- Reavaliar **formas de pagamento** e comunicação com clientes que usam fatura digital.

---

## 🔮 Próximos Passos

- Construção de um **modelo preditivo de churn** com aprendizado supervisionado.
- Aplicação de **clusterização** para segmentação dos clientes.
- Desenvolvimento de um **painel interativo** com Dash ou Streamlit.

---

## 🧪 Tecnologias Utilizadas

- Python 3.10+
- Pandas
- NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

---

## ▶️ Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/TheGabrielVieira/challenge2-data-science.git
```

2. Crie um ambiente virtual:
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate   # Windows
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Execute o notebook:
```bash
jupyter notebook

```

---

## 👤 Autor

Projeto desenvolvido por **Gabriel Vieira** como parte do Challenge da Trilha de Especialização em Data Science do **Programa ONE: Oracle Next Education** em parceria com a **Alura**.

---