FROM node:alpine
WORKDIR /app/first-proj
COPY ./first-proj/package.json .
RUN npm install
COPY ./first-proj/ .
CMD ["npm", "run","server1"]