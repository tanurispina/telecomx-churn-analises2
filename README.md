# 📡 Telecom X:

Este projeto foi desenvolvido como parte do **desafio final de Machine Learning da formação em Ciência de Dados da Alura**, integrada ao programa de especialização da **Oracle**.  

O foco principal é a construção de um **pipeline preditivo para identificar a evasão de clientes (Churn)** da empresa fictícia **Telecom X**.

---

# 📝 Resumo do Projeto

O **Churn** é uma das métricas mais críticas para empresas de serviços. Identificar precocemente clientes que pretendem cancelar o contrato permite a implementação de **estratégias de retenção personalizadas**, reduzindo prejuízos e otimizando o **custo de aquisição de novos clientes (CAC)**.

Este projeto abrange desde o **tratamento inicial dos dados (limpeza e tipagem)** até a **análise de importância das variáveis**, comparando **modelos estatísticos e de conjunto (ensemble)** para obter a melhor performance de negócio.

---

```markdown
## Tecnologias utilizadas

Python • Pandas • Scikit-Learn • Matplotlib • Seaborn • Google Colab
```

# 🔍 Principais Insights e Resultados

Após a análise exploratória e a modelagem, os seguintes padrões foram identificados como cruciais para a evasão:

### 📄 Tipo de Contrato
Clientes com **contratos mensais** possuem uma propensão de cancelamento **drasticamente superior** aos clientes com contratos anuais.

### ⏳ Tempo de Casa (Tenure)
O risco de saída é **crítico nos primeiros 6 meses** de relacionamento. Após o primeiro ano, a fidelidade tende a **se estabilizar**.

### 🌐 Tecnologia
Usuários de **fibra óptica** apresentaram taxas de evasão **acima da média**, sugerindo a necessidade de revisão na **qualidade do serviço ou na estratégia de preços**.

### 🤖 Performance do Modelo
A **Regressão Logística** foi selecionada como modelo final devido ao seu excelente equilíbrio entre:

- **Interpretabilidade**
- **Recall** (capacidade de detectar clientes que realmente sairiam)

---

# 🛠️ Como Executar o Projeto

## 1️⃣ Via Google Colab (Recomendado)

1. Faça o download do arquivo `TelecomX_BR2.ipynb` deste repositório.

2. Acesse o **Google Colab**

3. Vá em:
Arquivo → Fazer upload do notebook

4. No menu lateral esquerdo (**ícone de pasta**), faça o upload do dataset:
telecom_churn_limpo.csv

5. No menu superior clique em:
Ambiente de execução → Executar tudo

---

## 2️⃣ Ambiente Local (VS Code / Jupyter)

### Pré-requisitos

- Python **3.8+**

### 1. Clone o repositório

```bash
git clone https://github.com/tanurispina/telecomx-churn-analises2
cd nome_do_repositorio
```

### 2. Instale as bibliotecas necessárias
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Execute o notebook
Abra o Jupyter Notebook ou utilize a extensão do Jupyter no VS Code para executar o arquivo .ipynb.

# ⚙️ Etapas do Desenvolvimento

## 🧹 Limpeza e Tipagem
* Ajuste de colunas numéricas
* Remoção de registros inconsistentes

## 🧠 Feature Engineering
* Aplicação de One-Hot Encoding para variáveis categóricas
* StandardScaler para normalização de variáveis numéricas

## 📊 Análise de Correlação

Investigação estatística das variáveis que mais impactam o Churn.

## 🤖 Treinamento de Modelos

Comparação entre:
* Regressão Logística
* Random Forest

## 📈 Avaliação de Métricas

Uso de:
* Matriz de Confusão
* Precision
* Recall
* F1-Score
para validação técnica dos modelos.

---

## 👤 Autor

### Tanuris Pina


#### 🎓 Especialização em Data Sciencie: Programa ONE + Alura.

## 📄 Licença
Este projeto é para fins educacionais e segue os termos de uso do programa de especialização Alura / Oracle.
