FROM node:14-alpine
COPY package*.json .
RUN npm install
COPY public ./public
COPY src ./src
COPY .env.development .
EXPOSE 3000
CMD ["npm","start"]
