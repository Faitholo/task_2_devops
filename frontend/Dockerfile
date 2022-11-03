# Filename: Dockerfile 
FROM node:16-alpine
WORKDIR /frontend/src/components
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm", "start"]