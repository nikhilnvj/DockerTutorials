from node:alpine

WORKDIR /usr/app
copy ./package.json ./
run npm install
copy ./ ./
cmd ["npm","start"]