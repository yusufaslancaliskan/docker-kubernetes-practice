FROM node:alpine


# placing our app into the folder
WORKDIR /usr/app

copy ./package.json ./
RUN npm install
COPY ./ ./

CMD ["npm","start"]