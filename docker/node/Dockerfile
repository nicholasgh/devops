# De onde deve ser pega a imagem e a versão. Nesse caso do repositório padrão do Docker, a imagem do node

# FROM node:alpine
FROM node:current-alpine

# Autor/Mantenedor
LABEL Nicholas GetHash 

# Prover camada de cached para os módulos do Node
# RUN cd /tmp && npm install

# RUN mkdir -p /src 
	# Instalar MariaDB SQL e rodar o script para injetar o SQL

# RUN npm install mysql
	# Definir diretório de trabalho
# WORKDIR /src
# ADD . /src

	# Expor porta 80
EXPOSE  3333

	# Rodar o app usando nodemon
CMD ["node", "/dist/shared/http/server.js"]