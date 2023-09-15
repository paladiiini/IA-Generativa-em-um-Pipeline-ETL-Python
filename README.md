# Explorando IA Generativa em um Pipeline de ETL com Python

Este repositório contém um projeto que demonstra como integrar uma IA generativa em um pipeline de ETL (Extract, Transform, Load) usando Python. O projeto utiliza várias bibliotecas e tecnologias para realizar as seguintes tarefas:

- Extração de dados de uma API externa.
- Processamento e transformação dos dados.
- Geração de conteúdo de IA para enriquecer os dados.
- Atualização dos dados na API externa.

## Repositório da API Externa

O projeto faz uso de uma API externa hospedada no GitHub. Você pode encontrar o repositório da API em [digitalinnovationone/santander-dev-week-2023-api](https://github.com/digitalinnovationone/santander-dev-week-2023-api).

Certifique-se de que a API esteja acessível e funcionando corretamente antes de executar o pipeline ETL.

## Configuração

Antes de executar o pipeline de ETL, é necessário configurar algumas variáveis de ambiente e bibliotecas. Certifique-se de seguir as instruções abaixo:

### Variáveis de Ambiente

- `openai_api_key`: Configure esta variável de ambiente com sua chave de API do OpenAI para a geração de conteúdo de IA.

### Bibliotecas Python

Instale as bibliotecas Python necessárias executando o seguinte comando:

```bash
pip install pandas requests openai
