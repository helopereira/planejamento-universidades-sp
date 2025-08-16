# 🎓 Análise de Expansão Universitária em São Paulo

Este projeto apresenta um sistema de apoio à decisão para o planejamento de novas unidades universitárias no estado de São Paulo. O sistema utiliza análise de dados para identificar as cidades mais adequadas para a instalação de uma unidade em cada mesorregião e sugere uma lista de cursos de graduação que se alinham com a demanda de empregabilidade local.

O objetivo é fornecer uma ferramenta estratégica para a direção de uma universidade, permitindo que a oferta educacional seja adaptada às necessidades econômicas e sociais de cada região, promovendo uma formação mais direcionada e aumentando a empregabilidade dos estudantes.

---

## 🗺️ Cenário e Problema

O projeto foi desenvolvido para atender à necessidade de uma universidade que planeja abrir uma unidade em cada uma das mesorregiões do estado de São Paulo. Cada nova unidade precisa ter, no mínimo, dez cursos de graduação distintos, com base em critérios de empregabilidade, recursos disponíveis e relevância socioeconômica.

O principal desafio é decidir:
1.  **Quais cursos** 📚 são mais adequados para cada mesorregião?
2.  **Em qual cidade** 🏙️ de cada mesorregião a unidade deve ser instalada?

---

## 🎯 Objetivos do Sistema

* **Análise e Definição de Cursos:** O sistema analisa dados de empregabilidade e demanda regional para recomendar os dez cursos mais relevantes para cada unidade.
* **Seleção da Cidade:** Identifica a cidade mais adequada em cada mesorregião para a instalação da unidade, baseando-se em fatores como população e concentração de estudantes.
* **Visualização em Mapa:** Gera um mapa 📍 que exibe as cidades escolhidas e a lista de cursos sugeridos para cada localidade.
* **Tomada de Decisão Estratégica:** Serve como uma ferramenta de apoio para que a universidade possa visualizar as oportunidades e ajustar sua oferta de cursos de acordo com o mercado de trabalho local.

---

## 📊 Fontes de Dados

Para o desenvolvimento do sistema, foram utilizadas diversas fontes de dados confiáveis e atualizadas:

* **INEP (Censo da Educação Superior):** Para identificar os cursos mais populares e com alta empregabilidade.
* **SEADE (Estatísticas de Emprego Formal):** Para analisar as áreas com maior número de empregos formais nos municípios.
* **IBGE:** Para o arquivo `shapefile` utilizado na criação dos mapas.
* **RAIS (Relação Anual de Informações Sociais):** Para informações socioeconômicas e do mercado de trabalho.
* **MEC (Ministério da Educação):** Para dados sobre a demanda de cursos nas cidades, auxiliando na escolha da maior cidade de cada mesorregião.

---

## ▶️ Como Executar o Sistema

O sistema foi desenvolvido em um notebook Python (Google Colab) e requer o download de arquivos adicionais para funcionar corretamente.

### 1. Acessar o Notebook

* Faça o download do arquivo sistema-tomada-de-decisão.ipynb e utilize-o para criar um novo notebbook com o Google Colab.

### 2. Baixar e Preparar os Arquivos

* Faça o download do arquivo compactado `decisao_uni.zip`.
* Descompacte o arquivo. Você obterá vários arquivos de dados (planilhas, shapefiles, etc.).
* Faça o upload de **todos os arquivos extraídos** para a aba **"Arquivos"** no ambiente do Google Colab.
* **Atenção:** Não renomeie os arquivos. Qualquer alteração nos nomes impedirá o funcionamento do sistema.

### 3. Executar o Notebook

* No Google Colab, execute todos os blocos de código em sequência, do início ao fim.
* O último bloco de código é o responsável por iniciar a aplicação.

### 4. Utilizar o Sistema

* Após a execução, siga as instruções que aparecerão na tela para interagir com o sistema, selecionar a mesorregião e definir a quantidade de cursos por área.
* O programa irá então exibir os cursos sugeridos e o mapa com a localização da nova unidade.

---

## 📄 Relatório Completo

Para uma análise mais aprofundada sobre a metodologia, os dados e os resultados do projeto, consulte o **relatório completo** disponível em **`relatorio.pdf`**. Este documento detalha as etapas de coleta e tratamento de dados, a lógica por trás das recomendações e os insights obtidos durante o desenvolvimento do sistema.
