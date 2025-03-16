FROM node:16.13.2
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["npm", "run", "start"]


# docker build -t alexanderba/aula-conversao-temperatura:v1 .
# docker container run -it -p 8080:8080 alexanderba/aula-conversao-temperatura:v1