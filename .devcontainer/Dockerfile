ARG NODE_V=14.7-slim
FROM node:${NODE_V}
RUN apt update && apt install -y git
RUN npm install webpack webpack-cli @vue/cli create-react-app pnpm -g
WORKDIR /app

# EXPOSE 8080