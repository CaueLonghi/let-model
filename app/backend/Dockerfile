# Use a imagem base do Node.js
FROM python:3.10

# Defina o diretório de trabalho dentro do contêiner
WORKDIR /usr/src/app

# Copie o arquivo package.json e package-lock.json para o diretório de trabalho
COPY . ./

# Instale as dependências do projeto
RUN pip install -r requirements.txt

# Exponha a porta 8800
EXPOSE 8000

# Defina o comando padrão para iniciar o aplicativo usando nodemon
CMD ["python", "backend.py"]
