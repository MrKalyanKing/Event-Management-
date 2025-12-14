FROM node:20-alpine

WORKDIR /app

COPY package*.json .

RUN npm install

COPY . .

EXPOSE 5173

# you need to start Vite with --host so it binds to 0.0.0.0.
CMD ["npm", "run", "dev", "--", "--host"]
