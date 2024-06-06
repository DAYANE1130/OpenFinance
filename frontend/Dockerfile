FROM node:16.14-alpine
WORKDIR /app-frontend
COPY package*.json ./

# Instale as dependências do projeto
RUN npm install

# Copie o resto dos arquivos do projeto para o diretório de trabalho
COPY . .
EXPOSE 3000

CMD [ "npm","run", "dev" ]