FROM node:16
WORKDIR /appbackend
COPY ./package*.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "dev"]