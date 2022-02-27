### HMV python api

Requisitos para rodar o projeto:
Python 3.6+

## Como rodar

Clone o projeto e acesse a pasta. Na raíz do projeto, criei um ambiente virtual com `python -m venv .venv`. Em seguida, ative o ambiente rodando `source .venv/bin/activate`.
Depois, instale as dependências com `pip install -r requirements.txt`.
Para rodar a api, utilize o comando `uvicorn main:app --reload` para rodar a api na porta `:8000`. Para acessar a documentação pelo Swagger UI, acesse `http://localhost:8000/docs`.
