# backend/Dockerfile
FROM node:22

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .
# COPY ./backend .

EXPOSE 3000 
CMD ["npm", "run", "start"]