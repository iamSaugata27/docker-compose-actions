FROM node:alpine
WORKDIR /app/second-proj
COPY ./second-proj/package.json .
RUN npm install
COPY ./second-proj/ .
CMD ["npm", "run","server2"]