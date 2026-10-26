## 📊 Análise de Carteira de Ações — VaR e Backtesting

Projeto de **Data Analytics aplicado à análise de risco financeiro**, com o objetivo de avaliar o *Value at Risk (VaR)* como medida de estimativa de perdas potenciais em uma carteira de ações e verificar seu desempenho por meio de backtesting com dados históricos.

### 🎯 Objetivos
- Avaliar o comportamento dos preços e retornos de 10 ativos da Bolsa de Valores.
- Mensurar riscos individuais e consolidados da carteira.
- Analisar volatilidade, correlação e benefícios da diversificação.
- Comparar as perdas estimadas pelo VaR com os resultados observados em períodos posteriores.

### 🛠️ Etapas e Técnicas Aplicadas
- **ETL e preparação de dados:** limpeza, transformação e estruturação da base histórica.
- **Análise Exploratória de Dados (EDA):** avaliação da evolução dos preços, retornos e volatilidade dos ativos.
- **Estatística aplicada:** análise de distribuição, histogramas e matriz de correlação.
- **Value at Risk (VaR):** estimativa de perdas potenciais com horizonte de 180 dias e nível de confiança de 95%.
- **Backtesting:** comparação entre períodos previstos e realizados, utilizando duas estratégias de segmentação temporal.

### 📈 Principais Resultados
- **10 ativos analisados**, com 492 dias de negociação entre 2019 e 2021.
- **R$ 1 milhão** em investimento fictício distribuído entre os ativos.
- **2,20% de volatilidade ponderada** da carteira, evidenciando o efeito da composição dos ativos sobre o risco.
- **VaR consolidado de -R$ 19.988,15**, inferior à soma dos VaRs individuais em módulo, demonstrando o benefício potencial da diversificação.
- No segundo modelo de backtesting, o VaR estimado foi de **-R$ 23.963,00**, enquanto o VaR observado no período posterior foi de **-R$ 18.098,47**.

### 💡 Conclusões
A análise demonstrou a utilidade do VaR como ferramenta de mensuração de risco, mas também suas limitações diante de mudanças nas condições de mercado e eventos extremos, como a pandemia de COVID-19.

O projeto reforça a importância da diversificação, da validação de modelos estatísticos e do uso combinado de indicadores para apoiar decisões financeiras mais fundamentadas.

> **Observação:** o VaR representa uma estimativa condicionada às premissas do modelo, não uma garantia de perda máxima.

### 🔗 Artigo completo
[Leia a análise completa no Medium](https://medium.com/@maironhenrique)
