FROM node:14-alpine

WORKDIR /usr/app
# COPY src dest
COPY ./package.json ./ 
RUN npm install
COPY ./ ./
CMD ["npm", "start"]





