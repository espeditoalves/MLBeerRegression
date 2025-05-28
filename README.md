- [1. 🍺 Previsão de Consumo de Cerveja - Regressão Linear](#1--previsão-de-consumo-de-cerveja---regressão-linear)
  - [1.1. 📌 Dataset](#11--dataset)
    - [1.1.1. 📊 Variáveis disponíveis:](#111--variáveis-disponíveis)
  - [1.2. 🎯 Objetivo](#12--objetivo)
  - [1.3. ⚙️ Tecnologias Utilizadas](#13-️-tecnologias-utilizadas)
  - [1.4. 📁 Estrutura do Projeto](#14--estrutura-do-projeto)
  - [1.5. 🚀 Como Executar](#15--como-executar)
  - [1.6. 📬 Contato](#16--contato)

# 1. 🍺 Previsão de Consumo de Cerveja - Regressão Linear

> Projeto de Machine Learning utilizando Regressão Linear para estimar o consumo de cerveja com base em variáveis climáticas e contextuais coletadas na cidade de São Paulo.

---

## 1.1. 📌 Dataset

**Fonte:** [Beer Consumption - Kaggle](https://www.kaggle.com/dongeorge/beer-consumption-sao-paulo)

**Descrição:**  
Os dados foram coletados em uma região universitária da cidade de São Paulo (Brasil), onde há alta concentração de jovens de 18 a 28 anos, frequentemente envolvidos em festas e eventos sociais.

---

### 1.1.1. 📊 Variáveis disponíveis:

| Variável     | Descrição                                 |
|--------------|--------------------------------------------|
| `data`       | Data da observação                         |
| `temp_media` | Temperatura média (°C)                     |
| `temp_min`   | Temperatura mínima (°C)                    |
| `temp_max`   | Temperatura máxima (°C)                    |
| `chuva`      | Precipitação (mm)                          |
| `fds`        | Final de semana (`1` = Sim, `0` = Não)     |
| `consumo`    | Consumo de cerveja (litros)                |

---

## 1.2. 🎯 Objetivo

> Estimar um modelo de **Machine Learning** com **Regressão Linear** para demonstrar o impacto das variáveis sobre o consumo de cerveja (`Y`). Ao final, teremos um modelo de predição baseado nas variáveis explicativas (`X`) para prever o consumo médio.

---

## 1.3. ⚙️ Tecnologias Utilizadas

O projeto utiliza o ambiente gerenciado com **Poetry** e os seguintes pacotes:

```toml
[tool.poetry.dependencies]
python = ">=3.10,<3.13"
pandas = ">=2.2.3,<3.0.0"
notebook = ">=7.4.2,<8.0.0"
ipykernel = ">=6.29.5,<7.0.0"
matplotlib = ">=3.10.3,<4.0.0"
seaborn = ">=0.13.2,<0.14.0"
scikit-learn = ">=1.6.1,<2.0.0"
```

---

## 1.4. 📁 Estrutura do Projeto

```
beer-consumption-ml/
├── data/
│   ├── raw/                         # Dados originais brutos
│   ├── processed/                   # Dados tratados/pré-processados
├── img/
├── models/
├── notebooks/
├── src/
├── tests/
├── README.md
├── poetry.lock 
├── pyproject.toml                  # Configuração do Poetry
└── .gitignore
```

---

## 1.5. 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/espeditoalves/MLBeerRegression.git
   cd beer-consumption-ml
   ```

2. Instale o ambiente com Poetry:
   ```bash
   poetry install
   ```

---

## 1.6. 📬 Contato

- ✉️ **E-mail:** [espedito.ferreira.alves@outlook.com](espedito.ferreira.alves@outlook.com) 
- 🔗 **LinkedIn:** [Espedito Ferreira Alves](https://www.linkedin.com/in/espedito-ferreira-alves/)  


