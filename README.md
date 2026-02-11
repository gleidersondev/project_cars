# Projeto Exposição de Carros Antigos

Este é um projeto de exposição de carros antigos desenvolvido em Python utilizando o framework Django. O projeto utiliza um banco de dados SQLite para armazenar informações sobre os carros.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **Django**: Framework web para desenvolvimento rápido.
- **SQLite**: Banco de dados leve e fácil de usar.

## Instalação

Siga os passos abaixo para configurar o projeto em sua máquina local:

1. **Clone o repositório**:
   ```bash
   git clone git@github.com:gleidersondev/project_cars.git
   cd project_cars
   ```

2. **Crie um ambiente virtual** (recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Para Linux/Mac
   venv\Scripts\activate  # Para Windows
   ```

3. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Migre o banco de dados**:
   ```bash
   python manage.py migrate
   ```

5. **Inicie o servidor**:
   ```bash
   python manage.py runserver
   ```

6. **Acesse a aplicação**:
   Abra seu navegador e vá para `http://127.0.0.1:8000`.

