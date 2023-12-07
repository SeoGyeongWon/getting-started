From node:12-alpine
WORKDIR /app
COPY . .
RUN yarn install --production --ignore-engines
CMD ["node", "src/index.js"]
