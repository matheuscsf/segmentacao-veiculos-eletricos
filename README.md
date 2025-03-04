# 🚗⚡ Segmentação de Proprietários de Veículos Elétricos

🔍 **Objetivo do Projeto**  
Este projeto tem como objetivo criar **perfis distintos de proprietários de veículos elétricos** a partir de dados reais, usando técnicas de **Machine Learning** e **Análise de Dados**. Para isso, utilizamos o algoritmo **K-Means** para segmentação, além de **PCA** para redução de dimensionalidade.

## 📊 **Sobre a Base de Dados**
Os dados foram obtidos a partir do Kaggle:  
🔗 [Electric Vehicle Population Data - Kaggle](https://www.kaggle.com/datasets/mzohaibzeeshan/electric-vehicle-population-data-messy-data)  

A base contém informações sobre veículos elétricos registrados, incluindo:  
- **Fabricante e Modelo**
- **Autonomia Elétrica**
- **Localização (cidade, estado, código postal)**
- **Tipo de Veículo** (_BEV_ - 100% elétrico ou _PHEV_ - híbrido plug-in)

---

## 📂 **Estrutura do Repositório**
```bash
📦 segmentacao-veiculos-eletricos
 ┣ 📂 data                # 📊 Dados originais e tratados
 ┣ 📂 notebooks           # 📒 Notebooks com cada etapa do projeto
 ┣ 📂 src                 # 🖥️ Código-fonte (funções e processamento)
 ┣ 📂 images              # 📸 Gráficos e visualizações
 ┣ 📂 reports             # 📄 Relatórios gerados
 ┣ 📄 README.md           # 📜 Documentação principal do projeto
 ┣ 📄 requirements.txt    # 📦 Dependências para rodar o projeto
 ┗ 📄 .gitignore          # 🚫 Arquivos ignorados pelo Git
```
---

## 🚀 **Como Rodar o Projeto**

1️⃣ Clone o repositório:

```bash
git clone https://github.com/matheuscsf/segmentacao-veiculos-eletricos.git
cd segmentacao-veiculos-eletricos
```

2️⃣ Instale as dependências

Crie um ambiente virtual e instale os pacotes necessários:

```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3️⃣ Execute os notebooks:

Abra o Jupyter Notebook e explore cada etapa do projeto:
```bash
jupyter notebook
```
---

## 🏆 Metodologia Aplicada
📌 1. Exploração dos Dados
- Analisamos os principais atributos e realizamos a limpeza dos dados.
📌 2. Tratamento e Normalização
- Convertendo variáveis categóricas em numéricas.
- Normalizando os dados para melhor performance do modelo.
📌 3. Redução de Dimensionalidade (PCA)
- Aplicamos PCA para reduzir a complexidade dos dados.
📌 4. Clusterização (K-Means)
- Escolhemos K = 3 usando o Método do Cotovelo.
- Criamos grupos distintos de proprietários com base nas características dos veículos.
📌 5. Visualização e Insights
- Criamos gráficos para interpretar os clusters.
- Identificamos perfis distintos de proprietários.

---

## 🔎 Principais Resultados

🎯 Identificamos 3 grupos principais de proprietários:
- 1️⃣ Proprietários de veículos elétricos acessíveis (híbridos com menor autonomia).
- 2️⃣ Proprietários de veículos elétricos premium (maior autonomia e marcas premium).
- 3️⃣ Perfil intermediário (mistura de modelos com autonomia mediana).

📊 Confira os detalhes na pasta ```reports/``` com o relatório completo!

---

## 📌 Tecnologias Utilizadas
- 🔹 Python 🐍
- 🔹 Pandas 📊
- 🔹 Scikit-Learn 🤖
- 🔹 Matplotlib & Seaborn 📈
- 🔹 Jupyter Notebook 📒


