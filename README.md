# Analise-de-Dados---Projeto-MatchLar
Parte de Análise de Dados do projeto da Uninove

# Guia de Execução do Projeto no Google Colab

Este documento tem como objetivo guiar o professor (ou qualquer outro usuário) na execução dos códigos deste projeto no ambiente do Google Colab, dado que o arquivo CSV foi salvo no Google Drive.

## Pré-requisitos:

*   Uma conta Google.
*   Acesso ao Google Drive.
*   O arquivo `dados_imobiliarios.csv` do projeto.

## 1. Configuração Inicial do Arquivo CSV no Google Drive:

**PASSO CRÍTICO:** Antes de iniciar, certifique-se de que o arquivo `dados_imobiliarios.csv` esteja salvo em uma pasta de sua preferência no seu Google Drive. Anote o caminho completo para este arquivo, pois ele será necessário em vários pontos do código.

**Exemplo de Caminho:** `/content/drive/MyDrive/Minha_Pasta_Projeto/dados_imobiliarios.csv`

## 2. Abrindo o Notebook no Google Colab:

1.  Acesse o link do projeto no GitHub.
2.  Clique no botão "Open in Colab" (ou faça o download do arquivo `.ipynb` e o abra no Colab).

## 3. Executando os Códigos no Colab:

Siga as instruções abaixo para executar cada seção do notebook. O projeto está estruturado com células de texto (Markdown) para títulos e células de código (Python).

### 3.1 Montar o Google Drive

**Crie uma célula de código (Code Cell) e execute o seguinte:**

```python
from google.colab import drive
drive.mount('/content/drive')
Ao executar, você será solicitado a autorizar o Colab a acessar seu Google Drive. Siga as instruções para autenticação.
3.2 Preparação do Caminho do Arquivo CSV
Crie uma célula de código (Code Cell) e adapte o file_path com o caminho onde você salvou seu arquivo CSV no Google Drive:

import pandas as pd

# =========================================
# ATENÇÃO: SUBSTITUA COM O CAMINHO CORRETO DO SEU ARQUIVO CSV NO GOOGLE DRIVE
# =========================================
file_path = '/content/drive/MyDrive/Projeto Gestão de Sistemas 2026/2. Análise de Dados/dados_imobiliarios.csv' # Exemplo
# Ou se você salvou em uma pasta mais simples:
# file_path = '/content/drive/MyDrive/sua_pasta/dados_imobiliarios.csv'
```

