FROM node:10-alpine
WORKDIR /app
COPY package*.json .
RUN npm install 
COPY routes ./routes
COPY models ./models
COPY server.js .
EXPOSE 3001
CMD ["node","server.js"]
