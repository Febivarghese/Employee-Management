FROM node:20.19-slim

WORKDIR /app

COPY ems/package*.json ./

RUN npm install

COPY ems/ .

CMD ["npm", "run", "dev", "--", "--host"]