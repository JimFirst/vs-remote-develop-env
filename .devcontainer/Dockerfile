ARG NODE_V=18-slim
FROM node:${NODE_V}
RUN apt-get update && apt-get upgrade && apt install git
RUN npm install webpack webpack-cli @vue/cli create-react-app pnpm -g