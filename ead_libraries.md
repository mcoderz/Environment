# 📊 Resumo das Bibliotecas de Análise Exploratória de Dados (EDA) com Python

Análise comparativa para ajudar na escolha da melhor ferramenta de análise financeira pessoal com foco em leitura de CSV, visualização e geração de relatórios.

---

## 1. [Sweetviz](https://github.com/fbdesignpro/sweetviz) 
- **Tipo**: Relatório automático (HTML)  
- **Interatividade**: ❌  
- **Uso**: Geração rápida de relatórios com estatísticas descritivas e comparação entre datasets.  
- **Ideal para**: Obter uma visão geral automatizada das suas finanças.  
- **Pontos Fortes**:
  - Destaques automáticos (ex: colunas com maior impacto).  
  - Comparação entre dois conjuntos de dados (ex: mês a mês).  
- **Limitações**:
  - Relatório estático (não interativo).  
  - Sem suporte nativo a dashboards.  

---

## 2. [PyGWalker](https://docs.kanaries.net/pygwalker) 
- **Tipo**: Dashboard interativo estilo Tableau  
- **Interatividade**: ✅  
- **Uso**: Análise visual com drag‑and‑drop e múltiplos tipos de gráficos.  
- **Ideal para**: Usuários que desejam explorar gastos e padrões de forma visual e dinâmica.  
- **Pontos Fortes**:
  - Interface rica e moderna.  
  - Uso direto com Pandas DataFrames.  
- **Limitações**:
  - Não gera relatórios prontos.  
  - Requer tempo para personalização.  

---

## 3. [AutoViz](https://github.com/AutoViML/AutoViz) 
- **Tipo**: Gráficos automáticos com pouco código  
- **Interatividade**: ❌  
- **Uso**: Geração rápida de gráficos diretamente de arquivos CSV.  
- **Ideal para**: Visualização inicial com poucos comandos.  
- **Pontos Fortes**:
  - Sem necessidade de limpeza ou preparação de dados.  
  - Boa variedade de gráficos.  
- **Limitações**:
  - Baixa customização.  
  - Sem dashboards ou relatórios exportáveis.  

---

## 4. [YData Profiling (ex‑Pandas Profiling)](https://docs.profiling.ydata.ai/) 
- **Tipo**: Relatório estatístico completo (HTML)  
- **Interatividade**: ❌  
- **Uso**: Análise profunda de variáveis, correlações, alertas e qualidade dos dados.  
- **Ideal para**: Auditoria e diagnóstico estatístico dos dados.  
- **Pontos Fortes**:
  - Relatórios altamente detalhados.  
  - Detecção de outliers, valores ausentes, cardinalidade.  
- **Limitações**:
  - Pode ser lento em grandes volumes de dados.  
  - Relatórios são mais técnicos.  

---

## 5. [mplfinance](https://github.com/matplotlib/mplfinance) 
- **Tipo**: Visualização especializada para finanças (gráficos de preço)  
- **Interatividade**: ❌  
- **Uso**: Gráficos de candlestick, OHLC, volume e indicadores financeiros.  
- **Ideal para**: Análise de séries temporais e investimentos.  
- **Pontos Fortes**:
  - Gráficos profissionais de mercado financeiro.  
  - Suporte a dados históricos.  
- **Limitações**:
  - Não é uma ferramenta de EDA genérica.  
  - Exige dados com estrutura específica (ex: datas e preços).  

---

📌 **Recomendações rápidas para finanças pessoais:**
- **Sweetviz** ou **YData Profiling** para relatórios automáticos e detalhados.  
- **PyGWalker** para dashboards dinâmicos e interativos.  
- **mplfinance** para visualização de ativos financeiros históricos.  
- **AutoViz** para insights rápidos com mínima codificação.  
- **CSVDash** ou **CsvDataAnalyzer** para usuários sem código.  
