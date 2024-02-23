FROM node:18.12.2
WORKDIR /app
COPY package*json ./
RUN  nmp install 
COPY . .
EXPOSE 8180
CMD ["node", "server.js"]
