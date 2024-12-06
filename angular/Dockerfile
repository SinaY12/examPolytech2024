FROM node:10

LABEL maintainer="prenom"

WORKDIR /usr/src/app

COPY . .

RUN npm run build

EXPOSE 4200

CMD ["npm", "start"]