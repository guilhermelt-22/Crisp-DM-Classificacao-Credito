# Classificação de Crédito com Random Forest

Este projeto implementa um modelo de aprendizado de máquina para classificação de crédito, utilizando o algoritmo Random Forest. O objetivo é avaliar a qualidade de crédito de clientes com base em características pessoais e financeiras, ajudando a mitigar riscos para instituições financeiras.

## Estrutura do Projeto

1. **Introdução**
   - O projeto busca classificar clientes como "bons" ou "maus" pagadores, com base em um conjunto de variáveis.
   - A abordagem segue o **CRISP-DM**, um padrão amplamente utilizado em ciência de dados.

2. **Objetivo**
   - Criar um modelo preditivo que ajude instituições financeiras a reduzir perdas financeiras ao identificar possíveis maus pagadores.

3. **Etapas do Projeto**
   - **1. Compreensão do Negócio**:
     - Contextualização do problema de classificação de crédito.
   - **2. Compreensão dos Dados**:
     - Análise exploratória de dados para identificar padrões e características relevantes.
   - **3. Preparação dos Dados**:
     - Limpeza, transformação e criação de variáveis que aprimoram o modelo.
   - **4. Modelagem**:
     - Treinamento de uma Random Forest com ajustes no parâmetro `n_estimators`.
   - **5. Avaliação**:
     - Avaliação do modelo com base em métricas como acurácia e matriz de confusão.
   - **6. Implantação**:
     - Simulação do impacto financeiro do modelo, considerando cenários de lucro/prejuízo.

## Resultados

- **Acurácia do Modelo**:
  - Modelo com `n_estimators=3`: 97,05%
  - Modelo com `n_estimators=5`: 97,19%
- **Matriz de Confusão**:
  - Avaliação do desempenho em termos de falsos positivos e falsos negativos.
- **Impacto Financeiro**:
  - Implementação de uma análise simples baseada em lucro e prejuízo, mostrando o benefício do modelo para o negócio.

## Requisitos

- Python 3.x
- Bibliotecas:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`

## Como Executar

1. Clone o repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```
2. Execute o notebook:
   - Abra o arquivo `Projeto 01 - Classificação de crédito.ipynb` em um ambiente Jupyter ou equivalente.
   - Siga as células passo a passo.

## Futuras Melhorias

- Implementação de técnicas de validação cruzada para otimizar o modelo.
- Exploração de outros algoritmos (ex.: XGBoost, Gradient Boosting).
- Integração do modelo em uma aplicação para tomada de decisão em tempo real.

## Autor

Guilherme Lauer Teófilo
