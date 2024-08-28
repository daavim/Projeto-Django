# Learning Log

Learning Log é uma aplicação web construída com Django que permite aos usuários registrar o que estão aprendendo ao longo do tempo.

## Funcionalidades

- Registro de aprendizado em diferentes tópicos.
- Autenticação de usuários para que cada um tenha seu próprio registro de aprendizado.
- Interface simples e fácil de usar.

## Tecnologias Utilizadas

- *Django*: Framework web utilizado para construir a aplicação.
- *SQLite*: Banco de dados usado para armazenar informações.
- *HTML/CSS*: Tecnologias front-end para construção da interface do usuário.

## Instalação

1. Clone o repositório:
    bash
    git clone https://github.com/seu-usuario/learning_log.git
    cd learning_log
    

2. Crie um ambiente virtual e ative-o:
    bash
    python3 -m venv ll_env
    source ll_env/bin/activate  # No Windows use `ll_env\Scripts\activate`
    

3. Instale as dependências:
    bash
    pip install -r requirements.txt
    

4. Aplique as migrações do banco de dados:
    bash
    python manage.py migrate
    

5. Crie um superusuário para acessar o admin do Django:
    bash
    python manage.py createsuperuser
    

6. Execute o servidor de desenvolvimento:
    bash
    python manage.py runserver
    

7. Acesse a aplicação em seu navegador:
    
    http://127.0.0.1:8000/
    


Desenvolvido por Davi Moreira.
