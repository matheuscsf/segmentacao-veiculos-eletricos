# 📂 Pasta `data/` - Dados do Projeto

Esta pasta contém os **dados utilizados no projeto** de **Segmentação de Proprietários de Veículos Elétricos**. Os arquivos aqui armazenados incluem a base de dados original e a versão pré-processada, garantindo transparência e reprodutibilidade da análise.

---

## 📊 **Arquivos Disponíveis**
| Arquivo                  | Descrição |
|--------------------------|--------------------------------------------------------------------------------------|
| `dataset.csv`           | 📥 Base de dados original, extraída do Kaggle. |
| `dataset_clean.csv`     | 🔍 Versão tratada e pronta para análise, com valores ausentes corrigidos e variáveis processadas. |

---

## 📥 **Fonte dos Dados**
Os dados foram obtidos a partir do Kaggle:  
🔗 [Electric Vehicle Population Data - Kaggle](https://www.kaggle.com/datasets/mzohaibzeeshan/electric-vehicle-population-data-messy-data)  

**📌 Atenção:** O arquivo original pode ser atualizado na plataforma Kaggle, por isso recomendamos verificar a versão mais recente se necessário.

---

## 🔍 **Transformações Aplicadas (dataset_clean.csv)**
A base `dataset_clean.csv` passou pelas seguintes etapas de **pré-processamento**:
- 🚀 **Tradução dos nomes das colunas** para português.
- 🛠️ **Tratamento de valores ausentes**, preenchendo ou removendo dados inconsistentes.
- 📊 **Conversão de variáveis categóricas em numéricas** para facilitar a modelagem.
- ⚙️ **Normalização das variáveis numéricas** para evitar viés no algoritmo K-Means.

Estas transformações garantem que os dados estejam prontos para análise e segmentação.

---
