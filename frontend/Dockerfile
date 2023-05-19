FROM mcr.microsoft.com/devcontainers/javascript-node:0-20

WORKDIR /app

COPY . .

RUN npm install

WORKDIR /app/react_app

RUN npm install

EXPOSE 5173

CMD ["npm", "run", "dev"]