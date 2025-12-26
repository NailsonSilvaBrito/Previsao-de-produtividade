🌾 Previsão de Produtividade Agrícola

A agricultura é uma das atividades mais antigas e essenciais da humanidade. No entanto, continua sendo altamente dependente das condições climáticas. Chuvas em excesso ou escassez, temperaturas extremas, radiação solar e umidade podem transformar uma safra promissora em um ano de prejuízos.

Este projeto nasceu da curiosidade: **quais fatores climáticos realmente explicam a variação da produtividade agrícola?**  
E mais: **será possível prever anos de baixa produtividade e antecipar riscos financeiros?**

Com base em uma base de dados histórica de clima e produção, este estudo aplica técnicas de **ciência de dados** para responder a essas perguntas. O trabalho foi dividido em etapas que vão desde a **limpeza e tratamento dos dados**, passando por **estatísticas descritivas e análises exploratórias**, até a construção de **modelos preditivos**.

---

## 🎯 Objetivo

O objetivo principal é **identificar padrões climáticos que influenciam diretamente a produtividade agrícola** e construir modelos que permitam:
- Antecipar cenários de risco.
- Estimar perdas financeiras em anos críticos.
- Definir o cenário climático ideal para máxima produtividade.
- Apoiar decisões estratégicas no setor agrícola.

---

## 📊 Estrutura do Projeto

1. **Limpeza e tratamento dos dados**
   - Remoção de duplicados e valores nulos
   - Padronização de nomes de colunas
   - Conversão de tipos de dados

2. **Estatísticas descritivas**
   - Médias, mínimos e máximos das variáveis
   - Distribuição da produtividade ao longo dos anos

3. **Análises exploratórias**
   - Produtividade: anos de maior/menor rendimento, tendência temporal
   - Precipitação: impacto da chuva acumulada, limites mínimos e excesso
   - Temperatura: efeito da média, dias >34°C e ponto ótimo
   - Radiação e umidade: correlações e influência relativa

4. **Perguntas de negócio**
   - Quais variações climáticas explicam melhor a produtividade?
   - Qual cenário ideal de clima para máxima produtividade?
   - Quais fatores foram críticos em anos de baixa produtividade?
   - Qual o risco financeiro de anos ruins?
   - É possível prever anos de baixa produtividade com base em padrões climáticos?

5. **Modelagem preditiva**
   - Regressão linear para prever produtividade
   - Classificação de risco (anos abaixo da média) com Random Forest
   - Avaliação de métricas (R², RMSE, precisão, recall, F1-score)

6. **Visualizações**
   - Heatmap de correlação
   - Gráficos de dispersão com regressão
   - Gráficos comparativos de anos bons vs ruins
   - Cenário climático ideal para máxima produtividade

---

## 🚀 Principais Insights

- A produtividade máxima ocorre em cenários de **chuva adequada**, **temperatura moderada** e **radiação elevada**.
- **Excesso de calor (dias >34°C)** e **chuva em excesso** reduzem eficiência.
- A **umidade média** influencia mais a produção total do que a produtividade por hectare.
- O risco financeiro em anos ruins pode ser significativo, justificando modelos de previsão.
- Modelos de classificação mostraram que padrões climáticos podem antecipar anos de baixa produtividade.

---

## 📂 Organização dos Notebooks

- `01_limpeza_tratamento.ipynb`
- `02_estatisticas_descritivas.ipynb`
- `03_analise_precipitacao.ipynb`
- `04_analise_temperatura.ipynb`
- `05_radiacao_umidade.ipynb`
- `06_modelos_predicao.ipynb`
- `07_conclusoes.ipynb`

---

## 🔮 Próximos Passos

- Testar modelos mais avançados (Random Forest, XGBoost).
- Criar dashboard interativo (Plotly/Dash ou Streamlit).
- Integrar dados externos (eventos climáticos globais como El Niño/La Niña).
- Simular cenários futuros: *“se chover X mm e a temperatura média for Y, a produtividade esperada é Z”*.

---

## 👨‍💻 Autor

Projeto desenvolvido por **Nailson**, como parte do portfólio de Ciência de Dados.

