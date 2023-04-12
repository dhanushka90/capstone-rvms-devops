FROM node:18.12.1-bullseye
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY ./src/ ./src/
COPY ./public/ ./public/
RUN npm run build
EXPOSE 3000
CMD ["npm","start"] 
