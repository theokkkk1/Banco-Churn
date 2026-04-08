# 📊 Análise de Churn - Plataforma NogTech

Projeto de análise de dados com foco na identificação de padrões de cancelamento (churn) em uma plataforma de cursos de tecnologia.

---

## 📌 Objetivo

A NogTech identificou uma queda na receita causada pelo aumento no cancelamento de assinaturas.
O objetivo deste projeto é:

* Identificar **quem cancela**
* Entender **por que os clientes estão cancelando**
* Gerar **insights acionáveis para reduzir o churn**

---

## 🧹 Etapas do Projeto

### 🔧 1. Limpeza de Dados

* Tratamento de valores nulos (NaN)
* Correção de erros de digitação (ex: `"quarenta_e_nove"`)
* Conversão de colunas para formato numérico
* Padronização dos dados

---

### 🔍 2. Análise Exploratória

Foram analisadas variáveis importantes como:

* Plano do cliente
* Tempo de uso (`meses_ativo`)
* Feedback do cliente (`feedback_score`)
* Quantidade de tickets de suporte
* Idade
* Valor mensal e gasto total

Também foram criadas variáveis auxiliares:

* `cancelou` → indicador de churn
* `risco_cancelamento` → clientes com maior probabilidade de churn

---

## 📊 Principais Análises

* Taxa de cancelamento por plano
* Feedback vs churn
* Suporte vs churn
* Tempo de uso vs churn
* Gasto total vs churn
* Correlação entre variáveis

---

## 🧠 Insights Obtidos

### 🔍 1. Insatisfação do cliente

Clientes com baixo **feedback_score** apresentam maior taxa de cancelamento.

➡️ Indica problemas na experiência do usuário.

---

### 🔍 2. Problemas com suporte

Clientes com muitos **tickets de suporte** tendem a cancelar mais.

➡️ Sugere dificuldades técnicas ou operacionais na plataforma.

---

### 🔍 3. Baixo engajamento inicial

Clientes com poucos **meses ativos** possuem maior taxa de churn.

➡️ A plataforma não está gerando valor nos primeiros meses.

---

### 🔥 Insight Extra

Clientes com:

* baixo feedback
* alto número de tickets

possuem alto risco de cancelamento.

➡️ Possível prever churn antes que aconteça.

---

## 📈 Conclusão

A análise mostra que o churn está diretamente relacionado à experiência do cliente.
Melhorias na usabilidade, suporte e retenção inicial podem reduzir significativamente o cancelamento.

---

## 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📂 Estrutura do Projeto

```
📁 projeto-churn
 ┣ 📄 AtividadeChurn.ipynb
 ┣ 📄 nogtech_churn.csv
 ┗ 📄 README.md
```

---

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone <seu-repositorio>
```

2. Instale as dependências:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Execute o notebook:

```bash
jupyter notebook
```

---

## 👨‍💻 Autor

Theo José Luna Leal
Projeto acadêmico de análise de dados
