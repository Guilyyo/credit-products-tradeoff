# credit-products-tradeoff
Trade-off entre crescimento, rentabilidade e risco em produtos de crédito ao consumidor no Brasil: Uma análise com dados do Banco Central para apoiar decisões de precificação e política de crédito.

# Trade-off entre crescimento, rentabilidade e risco em produtos de crédito ao consumidor no Brasil

## Objetivo do Projeto
Este projeto tem como objetivo analisar o trade-off entre crescimento da carteira de crédito (proxy: crescimento), rentabilidade (proxy: taxa de juros) e risco (proxy: inadimplência) em produtos de crédito ao consumidor no Brasil.  
A análise utiliza dados públicos do Banco Central do Brasil para gerar insights que possam apoiar decisões de precificação e política de crédito em produtos financeiros, como cartões e crediário no varejo.

## Perguntas de Negócio
- Como a variação da taxa de juros impacta o crescimento da carteira de crédito ao consumidor?
- Existe relação entre taxa de juros e inadimplência?
- Quais cenários macroeconômicos tendem a favorecer crescimento vs. maior controle de risco?
- Como esse trade-off pode apoiar decisões de produto financeiro (precificação e política de crédito)?

## Fontes de Dados
Os dados utilizados são públicos e provenientes do Banco Central do Brasil (BCB), incluindo:
- Taxa média de juros do crédito ao consumidor (Pessoas Físicas);
- Inadimplência do crédito ao consumidor;
- Saldo da carteira de crédito ao consumidor.

## Metodologia (em desenvolvimento)
- Coleta e organização dos dados em banco local;
- Tratamento e consolidação das séries temporais;
- Análise exploratória das relações entre juros, crescimento da carteira e inadimplência;
- Análises estatísticas simples (correlação e regressão) para entender relações entre variáveis;
- Interpretação dos resultados sob a ótica de produtos financeiros e planejamento.

## Resultados Esperados
Espera-se identificar padrões e relações entre crescimento, rentabilidade e risco, de forma a:
- Apoiar decisões sobre quando priorizar crescimento de carteira;
- Indicar momentos em que é mais adequado focar em rentabilidade ajustada ao risco;
- Contribuir para reflexões sobre política de crédito em diferentes cenários de mercado.

## Estrutura do Repositório
- `data/raw`: dados brutos obtidos das fontes públicas;
- `data/processed`: dados tratados e consolidados para análise;
- `notebooks`: notebooks em Python com as etapas de análise;
- `src`: scripts auxiliares (ex.: consultas SQL);
- `README.md`: documentação do projeto.

## Observações
Este projeto é educacional e tem como objetivo o aprendizado prático em análise de dados aplicada a finanças e produtos financeiros.  
Os resultados não devem ser interpretados como recomendações financeiras reais, mas como um exercício analítico com base em dados públicos.

---
Projeto em desenvolvimento.
