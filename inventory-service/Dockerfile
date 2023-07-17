FROM node:19.7.0-slim
WORKDIR /app
COPY package* .
RUN npm install --production
COPY . .
EXPOSE 5002
CMD ["npm","start"]