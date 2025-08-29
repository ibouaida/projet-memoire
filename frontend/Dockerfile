FROM node:14

WORKDIR /app

COPY package.json ./
RUN npm install

COPY . .

EXPOSE 3000
# Important pour que react-scripts écoute sur 0.0.0.0
ENV HOST 0.0.0.0

CMD ["npm", "start"]
