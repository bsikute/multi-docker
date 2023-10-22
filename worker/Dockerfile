FROM node:16-alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install
COPY . .

COPY --chown=node ./ ./
CMD [ "npm", "run", "start" ]