# Análise de Rentabilidade de Carteiras de Investimentos

## Descrição do Projeto
Este projeto tem como objetivo realizar uma análise de rentabilidade de carteiras de investimentos utilizando dados financeiros reais. A análise busca identificar padrões de desempenho entre diferentes ativos (ações, títulos e fundos) ao longo de um período específico, considerando variações de risco e retorno.

Os principais cálculos feitos incluem:
- **Cálculo de VaR (Valor em Risco)** para medir o risco de perda da carteira.
- **Análise de correlação** entre os ativos antes e depois da pandemia.
- **Utilização de gráficos de desempenho** para avaliar a recuperação de ativos após eventos de crise.

## Como os Cálculos Foram Feitos
### 1. **Cálculo do Retorno Diário dos Ativos:**
   - O retorno diário de cada ativo foi calculado usando a fórmula:
     ```
     Retorno = (Preço de fechamento de hoje / Preço de fechamento de ontem) - 1
     ```

### 2. **Cálculo do RDP (Retorno Diário Ponderado):**
   - O retorno de cada ativo foi ponderado pela alocação percentual na carteira. A fórmula utilizada foi:
     ```
     RDP = Retorno Diário * Percentual Investido no Ativo
     ```

### 3. **Cálculo do VaR (Valor em Risco):**
   - O VaR foi calculado usando o percentil de 5% dos retornos diários de cada ativo.
     ```
     VaR = Valor Investido no Ativo * Percentil de 5% do Retorno Diário
     ```
   - O VaR da carteira foi então calculado somando os VaRs de cada ativo e obtendo o percentil de 5% da carteira total.

### 4. **Análise de Correlação:**
   - A correlação entre os ativos foi analisada comparando os períodos antes e depois da pandemia, verificando como o comportamento dos ativos mudou ao longo do tempo.

## Ferramentas Usadas
- **Microsoft Excel** foi utilizado para:
  - Realizar todos os cálculos de retorno, risco e VaR.
  - Criar gráficos para visualização da performance dos ativos.
  - Aplicar fórmulas de correlação e análises de risco-retorno.

## Como Replicar a Análise
1. **Baixar o Arquivo Excel**:
   - Faça o download do arquivo Excel fornecido [aqui](link_para_o_arquivo).
2. **Explorar as Planilhas**:
   - Cada planilha contém uma etapa específica da análise, incluindo o cálculo dos retornos, RDP, VaR e as correlações.
3. **Ferramentas**:
   - Apenas Microsoft Excel é necessário para abrir e entender as análises. Todos os cálculos e gráficos estão disponíveis dentro do arquivo Excel.

## Contato
Se você tiver qualquer dúvida ou quiser discutir mais sobre a análise, entre em contato:
- [LinkedIn](https://www.linkedin.com/in/seu-perfil)
