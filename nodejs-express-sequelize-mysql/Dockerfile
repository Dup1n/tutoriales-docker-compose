FROM node:14

ENV PORT=8080
ENV DB_HOST=localhost
ENV DB_USER=root
ENV DB_PASSWORD=mipassword
ENV DB_DATABASE=tutoriales

WORKDIR /app-node

COPY package.json .

RUN npm install

COPY . .

CMD npm start