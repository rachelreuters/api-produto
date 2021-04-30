#biblioteca para instalacao
FROM node:14.16.1-alpine3.13
#diretorio de trabalho
WORKDIR /app 

#copia para o diretorio corrente que é o Workdir
COPY package*.json ./
#EXECUTA comando
RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "app.js"]
