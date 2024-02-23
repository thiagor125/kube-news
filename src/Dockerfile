FROM node:18.12.1
WORKDIR /app
COPY package*json ./
RUN  nmp install 
COPY . .
EXPOSE 8180
CMD ["node", "server.js"]
