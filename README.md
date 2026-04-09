# 🎮 Projeto Integrado 1 — Análise de Vendas de Jogos Digitais

> Projeto integrado desenvolvido no bootcamp [TripleTen](https://tripleten.com/), consolidando habilidades de **limpeza de dados**, **análise exploratória**, **estatística** e **testes de hipóteses** aplicadas ao mercado de games.

---

## 📌 Sobre o Projeto

Este projeto consiste em uma análise completa de um dataset histórico de vendas de jogos digitais, com o objetivo de identificar padrões e tendências que possam orientar campanhas publicitárias e estratégias de lançamento para o **ano seguinte**.

O analista atua como consultor de uma loja online de jogos globais que precisa descobrir quais plataformas, gêneros e regiões têm maior potencial de vendas, além de validar hipóteses sobre preferências dos usuários.

---

## 🎯 Objetivos

- Limpar e preparar o dataset histórico de vendas de jogos
- Identificar as **plataformas mais rentáveis** e analisar seu ciclo de vida
- Descobrir os **gêneros mais vendidos** por região (América do Norte, Europa, Japão)
- Traçar **perfis de usuário** por região geográfica
- Testar hipóteses estatísticas sobre avaliações de usuários e críticos
- Gerar recomendações para o planejamento de campanhas do próximo ano

---

## 🗂️ Estrutura do Repositório

```
📁 Projeto-Integrado-1/
│
├── 📓 projeto integrado 1 - tripleten.ipynb   # Notebook principal com toda a análise
└── 📄 README.md                               # Documentação do projeto
```

---

## 📦 Dataset

O dataset contém registros históricos de jogos lançados entre os anos 1980 e 2016, com as seguintes colunas:

| Coluna | Descrição |
|---|---|
| `Name` | Nome do jogo |
| `Platform` | Plataforma (PS4, Xbox, PC, etc.) |
| `Year_of_Release` | Ano de lançamento |
| `Genre` | Gênero do jogo |
| `Publisher` | Empresa publicadora |
| `NA_sales` | Vendas na América do Norte (milhões) |
| `EU_sales` | Vendas na Europa (milhões) |
| `JP_sales` | Vendas no Japão (milhões) |
| `Other_sales` | Vendas em outras regiões (milhões) |
| `Global_sales` | Vendas globais totais (milhões) |
| `Critic_Score` | Nota da crítica especializada (0–100) |
| `User_Score` | Nota dos usuários (0–10) |
| `Rating` | Classificação etária (ESRB) |

---

## 🔍 Etapas da Análise

### 1. Pré-processamento dos Dados
- Padronização de nomes de colunas
- Tratamento de valores ausentes e duplicatas
- Conversão de tipos de dados (`Year_of_Release`, `User_Score`)
- Análise da abrangência temporal dos dados e definição do período relevante

### 2. Análise Exploratória Geral
- Distribuição de lançamentos por ano e plataforma
- Identificação das plataformas com maior volume de vendas globais
- Análise do **ciclo de vida** das plataformas ao longo do tempo
- Boxplot de vendas por plataforma para detectar outliers

### 3. Influência das Avaliações nas Vendas
- Correlação entre `Critic_Score` e `Global_sales`
- Correlação entre `User_Score` e `Global_sales`
- Comparação entre o impacto das notas da crítica vs. dos usuários

### 4. Análise por Gênero
- Ranking dos gêneros mais vendidos globalmente
- Gêneros mais lucrativos vs. mais populares (volume de títulos)

### 5. Perfis de Usuário por Região
- Top 5 plataformas em NA, EU e JP
- Top 5 gêneros em NA, EU e JP
- Impacto do rating ESRB nas vendas por região
- Diferenças culturais no consumo de jogos entre as regiões

### 6. Testes de Hipóteses
- **Hipótese 1:** As avaliações médias dos usuários para as plataformas *Xbox One* e *PC* são iguais
- **Hipótese 2:** As avaliações médias dos usuários para os gêneros *Action* e *Sports* são diferentes
- Escolha do nível de significância, formulação das hipóteses (H₀ e H₁) e interpretação dos resultados

### 7. Conclusões e Recomendações
- Síntese dos padrões identificados
- Recomendações estratégicas para campanhas do ano seguinte
- Identificação das apostas mais promissoras em plataforma, gênero e região

---

## 🛠️ Tecnologias Utilizadas

| Ferramenta | Finalidade |
|---|---|
| Python 3 | Linguagem principal |
| Pandas | Manipulação e limpeza de dados |
| NumPy | Cálculos numéricos |
| Matplotlib | Visualização de dados |
| Seaborn | Gráficos estatísticos |
| SciPy | Testes de hipóteses estatísticas |
| Jupyter Notebook | Ambiente de desenvolvimento interativo |

---

## ▶️ Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/caguiar0/Projeto-Integrado-1.git
```

2. Acesse a pasta do projeto:
```bash
cd Projeto-Integrado-1
```

3. Instale as dependências:
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

4. Inicie o Jupyter Notebook:
```bash
jupyter notebook
```

5. Abra o arquivo `projeto integrado 1 - tripleten.ipynb` e execute as células sequencialmente.

---

## 📊 Principais Conclusões

> ⚠️ *Preencha esta seção com os resultados reais obtidos na sua análise, como:*
> - Quais plataformas foram identificadas como mais promissoras para o próximo ano
> - Quais gêneros apresentaram melhor desempenho por região
> - Resultado dos testes de hipóteses (rejeitar ou não rejeitar H₀)
> - Recomendações finais para a estratégia de marketing da loja

---

## 🏅 Habilidades Demonstradas

- ✅ Limpeza e preparação de dados reais com valores ausentes
- ✅ Análise exploratória de dados (EDA) com visualizações
- ✅ Análise estatística e correlação entre variáveis
- ✅ Testes de hipóteses com interpretação de p-valor
- ✅ Geração de insights de negócio orientados a dados
- ✅ Comunicação de resultados em formato narrativo no notebook

---

## 👤 Autor

**caguiar0**  
Projeto desenvolvido como parte do currículo de Análise de Dados da [TripleTen](https://tripleten.com/).

---

## 📄 Licença

Este projeto é de uso educacional e está disponível para fins de estudo e portfólio.
