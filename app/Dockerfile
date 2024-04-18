#Imagem base do Python
FROM python:3.10.12

# Código da aplicação para o contêiner
COPY . /app
WORKDIR /app

# Dependências do Flask
RUN pip install -r requirements.txt

# Porta em que a aplicação Flask será executada
EXPOSE 8000

# Comando para iniciar a aplicação Flask
CMD ["python3", "api.py"]
