# About
Projeto final do curso de Desenvolvedor Full Stack Python da EBAC.
Consiste em um projeto baseado na ideia do Twitter, com feed, tweets, perfis etc.
Neste projeto é utilizado o backend em Django Rest Framework e o frontend adaptado no Streamlit, utilizando o próprio python.

# Getting Started
Estas instruções irão fornecer uma cópia do projeto em funcionamento na sua máquina local para fins de desenvolvimento e teste.

# Prerequisites
Quais itens você precisa para instalar o software e como instalá-los.

Python 3.11.x

python --version
# Installing
Crie um ambiente virtual:

python -m venv venv
Instale as dependências necessárias:

pip install -r requirements.txt
Primeiramente, realize os testes do Django:

python manage.py test
Execute o Django Rest em um terminal:

python manage.py runserver
Em outro terminal, execute o streamlit:

streamlit run app.py