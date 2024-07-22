# Sistema de Consulta a Restaurantes

## Descrição
Este projeto é uma aplicação Python que utiliza FastAPI para criar uma API que permite aos usuários consultar dados de restaurantes. Ele interage com uma API externa para obter informações sobre restaurantes e disponibiliza esses dados através de endpoints próprios.

## Funcionalidades
- **Consulta de Restaurantes**: Permite consultar todos os restaurantes disponíveis ou detalhes específicos de um restaurante através de endpoints.
- **Serviço de API**: Fornece um serviço de API que responde com dados em formato JSON.

## Tecnologias Utilizadas
- Python
- FastAPI
- Requests

## Estrutura do Projeto
- `main.py`: Arquivo principal que configura os endpoints da API usando FastAPI.
- `app.py`: Script Python para buscar dados de uma API externa e salvar em arquivos JSON locais.
- `requirements.txt`: Lista todas as bibliotecas necessárias para executar a aplicação.

## Como Executar
Certifique-se de ter Python e pip instalados. Instale as dependências com:

```bash
pip install -r requirements.txt

uvicorn main:app --reload

