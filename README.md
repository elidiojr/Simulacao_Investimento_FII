# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

## 🎯 Descrição do Projeto

Este projeto foi desenvolvido como parte do desafio de projeto. O objetivo era criar uma ferramenta prática no Excel para simular investimentos em Fundos de Investimento Imobiliário (FIIs), aplicando conceitos financeiros e de automação de planilhas.

A ferramenta permite que o usuário insira parâmetros chave, como aporte mensal, preço da cota e rendimento de dividendos, para visualizar a projeção de seu patrimônio, a evolução da renda passiva e o famoso efeito "bola de neve" ao longo do tempo.

## ✨ Funcionalidades

- **Simulação Personalizada:** O usuário pode definir o valor do aporte mensal, preço da cota, dividend yield e o período da simulação.
- **Reinvestimento Automático:** A planilha calcula e reinveste automaticamente os dividendos recebidos, potencializando o crescimento do patrimônio.
- **Cálculo de Valorização da Cota:** Inclui um campo para simular a valorização (ou desvalorização) anual das cotas do fundo.
- **Dashboard Interativo:** Apresenta um resumo claro dos resultados finais, incluindo:
  - Patrimônio Final Acumulado
  - Total Investido vs. Ganhos Totais
  - Renda Passiva Mensal no final do período
- **Visualização Gráfica:**
  - **Patrimônio vs. Total Investido:** Um gráfico de linha que demonstra o crescimento exponencial dos juros compostos.
  - **Evolução dos Dividendos:** Um gráfico de barras que mostra o crescimento da renda passiva mensal ao longo do tempo.

## 🛠️ Tecnologias e Conceitos Utilizados

- **Microsoft Excel:**
  - Fórmulas Financeiras e Matemáticas (`SOMA`, `INT`, Potenciação `^`)
  - Funções de Referência e Lógica (`ÍNDICE`, `CONTA.VALORES`)
  - Referências Absolutas (`$B$2`) e Relativas (`A9+1`) para automação dos cálculos.
  - Formatação Condicional e Validação de Dados para uma melhor experiência do usuário.
  - Criação de Gráficos e Dashboards para visualização de dados.
- **Conceitos Financeiros:**
  - Juros Compostos (Efeito "Bola de Neve")
  - Dividend Yield (Rendimento de Dividendos)
  - Reinvestimento de Proventos
  - Apreciação de Ativos

## 🚀 Como Usar

1. Faça o download do arquivo `simulador_fii.xlsx`.
2. Abra o arquivo no Microsoft Excel.
3. Altere os valores na seção **"Parâmetros da Simulação"** para refletir o cenário que você deseja simular.
4. A tabela de simulação e o dashboard serão atualizados automaticamente.
5. Explore os gráficos para ter uma visão clara do potencial do seu investimento.
