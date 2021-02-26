FROM node:alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
COPY . .
# dev is for local development env, start is for production environment
# CMD ["npm", "run", "dev"]
CMD ["npm", "run", "start"]