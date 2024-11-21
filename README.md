# Trabalho 2 - Portfólios Multifatores

Este projeto explora a criação e avaliação de portfólios otimizados utilizando fatores multifatoriais baseados em dados financeiros. O objetivo é identificar estratégias eficientes de alocação de ativos e compará-las com índices de referência como o IBX e a SELIC.

## 📊 **Descrição do Projeto**
A análise é realizada com base em fatores financeiros extraídos de ativos do índice **IBX**, com dados cobrindo o período de **2005 a 2021**. Os fatores analisados incluem:
- **Qualidade**: Retorno sobre o capital investido (ROIC).
- **Momentum**: Retorno acumulado nos últimos 12 meses.
- **Tamanho**: Valor de mercado das empresas.
- **Valor**: Indicador Preço/Valor Patrimonial (PVP).
- **Volatilidade**: Volatilidade dos retornos nos últimos 12 meses.

Os portfólios são avaliados com diferentes métodos de otimização, como:
1. **Risk Parity (RP)**.
2. **Global Minimum Variance (GMV)**.
3. **Maximum Decorrelation Portfolio (MDP)**.

---

## 🚀 **Principais Funcionalidades**
1. **Análise de Fatores**:
   - Rankeamento de ativos com base nos fatores financeiros.
   - Combinação de múltiplos fatores para criar portfólios.
2. **Construção de Portfólios**:
   - Seleção de ativos com base no rankeamento.
   - Aplicação de métodos de otimização para alocação eficiente.
3. **Avaliação de Performance**:
   - Retorno acumulado e anualizado.
   - Volatilidade e drawdown.
   - Relação Retorno/Volatilidade.
   - Alpha e Beta em relação ao índice IBX.
4. **Visualizações**:
   - Gráficos de evolução de cotas.
   - Comparação de volatilidade.
   - Retornos anuais e desempenho relativo.

---

## 📈 **Resultados**
### Estatísticas dos Portfólios Otimizados
| Método                  | Retorno Anualizado | Volatilidade | Retorno/Volatilidade | Drawdown |
|-------------------------|--------------------|--------------|-----------------------|----------|
| **Risk Parity (RP)**    | 21,22%            | 18,35%       | 1,16                 | -33,4%   |
| **Global Min. Variance**| 18,23%            | 19,03%       | 0,96                 | -33,47%  |
| **Max. Decorrelation**  | 19,90%            | 18,98%       | 1,05                 | -33,16%  |

---

## 📂 **Como Executar**
1. Clone este repositório:
   ```bash
   git clone https://github.com/gianmalfate/multifactor-portfolio-optimization.git
2. Instale as dependências necessárias:
    ```bash
    pip install numpy pandas matplotlib riskfolio-lib==6.1.1
3. Execute o notebook:
    ```bash
    jupyter notebook Trabalho_2_Portfolios_Multifatores.ipynb

## 🛠 Tecnologias Utilizadas
- Python
- Bibliotecas:
    - numpy
    - pandas
    - matplotlib
    - Riskfolio-Lib

## 📧 Contato

Para dúvidas ou sugestões, entre em contato:

- Email: gianmalfate@gmail.com
- LinkedIn: Giancarlo Malfate Caprino
