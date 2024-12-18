Painel Interativo de Análise do Sistema Prisional Brasileiro
================

Este projeto apresenta um **painel interativo** desenvolvido com o R e o
**Shiny** para análise de dados do sistema prisional brasileiro. Ele
fornece visualizações como tabelas, gráficos e mapas, permitindo a
filtragem e exploração dinâmica de informações por estado, ano, gênero e
tipo de gráfico.

------------------------------------------------------------------------

## 📋 Funcionalidades

### 1. Tabela de Dados

- Visualização tabular dos dados filtrados.
- Opção de download no formato CSV.

### 2. Gráficos Interativos

- Visualização por linhas ou barras.
- Ajuste da escala (normal ou logarítmica).
- Download do gráfico como imagem PNG.

### 3. Mapa Interativo

- Exibição dos valores por estado.
- Paleta de cores para indicar intensidade dos valores.
- Opção de download do mapa no formato PNG.

### 4. Filtros Dinâmicos

- Filtros para:
  - Sexo (Ambos, Feminino, Masculino).
  - Estados (Seleção múltipla).
  - Período (2018 a 2023).
  - Tipo de gráfico (Linhas ou Barras).
  - Escala (Normal ou Logarítmica).
- Botão para resetar filtros.

------------------------------------------------------------------------

## 📂 Estrutura do Projeto

- **`dados.csv`**: Arquivo principal contendo os dados do sistema
  prisional.
- **`config.yaml`**: Arquivo de configuração para parâmetros adicionais
  (e.g., número de linhas na tabela).
- **R scripts**: Contém a implementação do painel interativo.
- **Site do Projeto**: <https://udinh0.shinyapps.io/presos/>
- **Site dos dados**:
  <https://publicacoes.forumseguranca.org.br/items/f62c4196-561d-452d-a2a8-9d33d1163af0>
