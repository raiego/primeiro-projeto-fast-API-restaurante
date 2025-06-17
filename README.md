# API de Restaurantes - FastAPI

API simples para consultar cardápios de restaurantes. 
Clone o repositório, crie um ambiente virtual, instale as dependências e rode a aplicação com o uvicorn. 
Use o endpoint `/api/hello` para testar se está funcionando e `/api/restaurantes/?restaurante=Nome` para obter o cardápio de um restaurante específico.

Para rodar, use os comandos:

```bash
git clone https://github.com/seu-usuario/repositorio.git
cd repositorio
python -m venv venv
venv\Scripts\activate  # Windows
pip install -r requirements.txt
uvicorn main:app --reload
