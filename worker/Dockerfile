FROM node:alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install
COPY . .
# Only different from the dev version.  See package.json for start script.
CMD ["npm", "run", "start"]