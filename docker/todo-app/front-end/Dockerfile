FROM node:14-alpine AS todofrontend
WORKDIR /app
COPY package*.json ./
ADD node_modules.tar.gz /app/node_modules
COPY . .
EXPOSE 3000
CMD ["npm", "start"]
