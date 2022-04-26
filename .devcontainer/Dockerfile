ARG NODE_V=18-slim
FROM node:${NODE_V}
RUN apt update && apt install -y git
RUN npm install webpack webpack-cli @vue/cli create-react-app pnpm -g
WORKDIR /vue3-test

EXPOSE 8080