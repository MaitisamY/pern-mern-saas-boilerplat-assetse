# frontend/Dockerfile
FROM node:22

WORKDIR /app

COPY package*.json ./
RUN npm install --force

COPY . .
# COPY ./frontend .

EXPOSE 5174
CMD ["npm", "run", "dev"]