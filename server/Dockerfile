FROM node:14.14.0-alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
COPY . .
# "dev" is for local dev environment, "start" is for production env
CMD ["npm", "run", "start"]