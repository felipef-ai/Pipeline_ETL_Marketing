# Marketing Data Analysis

## Análise de Campanhas para Marketing Digital


Este projeto oferece uma solução completa para análise, validação e visualização de dados de campanhas de marketing digital. Com funcionalidades automatizadas e dashboards interativos, ele auxilia na tomada de decisões estratégicas, garantindo a qualidade e confiabilidade dos dados.

## 🚀 Funcionalidades

✅ Validação de Dados

Processamento automatizado de planilhas de campanhas utilizando Pydantic para garantir a integridade e consistência dos dados.

Upload de arquivos CSV contendo dados de campanhas.

Validação automática conforme o modelo de dados definido.

Exibição de erros de validação, caso existam.

Opção para baixar os dados validados após o processamento.


## 📈 Dashboard Interativo

Visualização intuitiva de KPIs essenciais para marketing digital, incluindo:

Gastos totais com campanhas;

Número de cliques e impressões;

Conversões e taxa de conversão;

Custo por Conversão (CPA);

Custo por Clique (CPC);

Taxa de Cliques (CTR);

Análise por Segmentação;

Exploração de dados por mês, com gráficos e métricas interativas.

## 📊 Geração de Relatórios Detalhados

Geração automática de relatórios completos de perfil de dados com ydata-profiling, permitindo uma visão aprofundada do desempenho das campanhas.

Os relatórios incluem:

Estatísticas descritivas sobre os dados;

Correlação entre variáveis, identificando padrões;

Distribuições de dados para melhor entendimento;

Detecção de valores ausentes e inconsistências;

Para gerar um relatório, execute:

`python main.py`

O script criará um arquivo HTML interativo com todas as análises.

## 📅 Modelo de Dados

O sistema valida e estrutura os seguintes campos das campanhas:

Organizador: ID do organizador da campanha

Ano_Mes: Período da campanha

Tipo de Anúncio: Formato do anúncio (Vídeo, Estático)

Segmentação: Tipo de segmentação utilizada

Métricas: Valores gastos, cliques, impressões e conversões

Outros detalhes da campanha essenciais para análise

## 💡 Como Usar

Clone o repositório:

https://github.com/felipef-ai/Pipeline_ETL_Marketing

Instale as dependências que estão listadas abaixo como "Tecnologias Utilizadas"

## 🛠 Tecnologias Utilizadas

Python 3.11.1;

Pydantic (para validação de dados);

Pandas (para manipulação de dados);

ydata-profiling (para relatórios analíticos);

Streamlit / Plotly (para dashboards interativos)

Setuptools 

📬 Contato

Se tiver dúvidas ou sugestões, sinta-se à vontade para entrar em contato!

## 📧 www.linkedin.com/in/felipe-fernandes-pinto-16843820