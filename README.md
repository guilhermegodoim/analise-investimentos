# 📊 Análise de Viabilidade de Projetos Energéticos (ESF vs EBM)

Este repositório contém a análise quantitativa e estratégica comparativa entre dois projetos de geração de energia renovável:  
- ☀️ **ESF** – Energia Solar Fotovoltaica, em Juazeiro (BA)  
- 🌱 **EBM** – Cogeração por Biomassa, em Chapecó (SC)

A análise segue a metodologia exigida na disciplina **CE839 – Análise de Projetos** (UNICAMP), com foco em avaliação econômica sob incerteza, utilizando **simulação de Monte Carlo** para mensuração de risco.

---

## 🧠 Objetivo

Apoiar a decisão de investimento entre os projetos propostos, considerando:

- Indicadores financeiros: **VPL**, **TIR** e **Payback**
- Análise de sensibilidade e risco
- Justificativas técnicas dos parâmetros utilizados
- Critérios estratégicos e operacionais qualitativos

---

## 🛠️ Tecnologias Utilizadas

- `Python 3`
- `NumPy`, `Matplotlib`
- Jupyter Notebooks
- Simulação de Monte Carlo (10.000 iterações por projeto)

## 📊 Indicadores Calculados

Todos os indicadores foram calculados a partir de distribuições dos seguintes parâmetros:

- **Preço da energia** (R$/MWh)
- **Eficiência operacional**
- **Custo variável**
- **Selic (anual)** e **IPCA (mensal → anual)**
- **Horizonte de 15 anos**

### 🔁 Indicadores:

| Indicador | Definição | Interpretação |
|----------|------------|----------------|
| `VPL`    | Valor Presente Líquido | Valor absoluto gerado pelo projeto |
| `TIR`    | Taxa Interna de Retorno | Rentabilidade percentual anual esperada |
| `Payback` | Tempo de retorno do investimento | Quanto tempo o projeto leva para "se pagar" |

---



