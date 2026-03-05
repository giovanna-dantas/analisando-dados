# 📊 Análise de Dados – Investigação de Cancelamento de Clientes (Churn)

Projeto de **análise exploratória de dados (EDA)** desenvolvido em Python com o objetivo de investigar padrões de comportamento associados ao cancelamento de clientes.

A análise busca transformar dados brutos em **insights que possam apoiar decisões estratégicas de negócio**, especialmente na redução da taxa de churn (taxa de cancelamento de clientes).

---

# Contexto do Problema

Uma empresa identificou um volume significativo de cancelamento de clientes em sua base.

A partir de uma base de dados com informações comportamentais e operacionais dos clientes, o objetivo deste projeto foi responder perguntas como:

- Qual a proporção de clientes que cancelaram o serviço?
- Existem padrões comportamentais associados ao cancelamento?
- Quais variáveis parecem ter maior impacto no churn?

Com essas respostas, torna-se possível orientar **estratégias de retenção de clientes**.

---

# Metodologia da Análise

O projeto seguiu um fluxo clássico de **análise exploratória de dados**:

### 1. Importação e exploração inicial dos dados

- leitura da base de dados
- verificação de estrutura da tabela
- análise das variáveis disponíveis

### 2. Limpeza e preparação dos dados

- identificação de valores ausentes
- remoção ou tratamento de inconsistências

### 3. Análise da variável alvo (cancelamento)

- cálculo da taxa de churn
- análise da distribuição de clientes que cancelaram vs. permaneceram

### 4. Análise exploratória das variáveis

- investigação da relação entre características dos clientes e cancelamento
- identificação de padrões relevantes

### 5. Visualização de dados

- construção de gráficos interativos para facilitar a interpretação dos resultados

---

# Tecnologias Utilizadas

- **Python**
- **Pandas** → manipulação e análise de dados
- **Plotly** → visualização de dados interativa
- **Jupyter Notebook** → ambiente de análise

---

# Principais Insights Identificados

A análise indicou alguns fatores potencialmente associados ao cancelamento de clientes:

**1️⃣ Tipo de contrato**

Clientes com contratos **mensais** apresentaram maior tendência ao cancelamento, possivelmente devido à menor barreira de saída.

**2️⃣ Interações com o suporte**

Um número elevado de contatos com o **call center** pode indicar experiências negativas ou problemas recorrentes no serviço.

**3️⃣ Histórico de pagamentos**

Clientes com **atrasos frequentes no pagamento** demonstraram maior probabilidade de cancelamento.

---

# Possíveis Aplicações de Negócio

Com base nos padrões identificados, algumas estratégias que poderiam ser consideradas incluem:

- incentivo a contratos de maior duração
- monitoramento preventivo de clientes com muitas interações no suporte
- criação de estratégias de retenção para clientes com risco de churn

---

# Objetivo do Projeto

Este projeto foi desenvolvido como prática para consolidar habilidades em **análise de dados com Python**, incluindo:

- exploração e compreensão de bases de dados
- limpeza e preparação de dados
- análise exploratória (EDA)
- identificação de padrões relevantes
- comunicação de insights através de visualizações

---

# Observação

Projeto desenvolvido para fins educacionais com o objetivo de praticar técnicas de **análise de dados e geração de insights a partir de dados reais**.
