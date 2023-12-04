FROM node:10-alpine
ADD ./code /app
WORKDIR /app
COPY code/* .
EXPOSE 8080
EXPOSE 3000
RUN npm install --save
RUN npm install --save sequelize sqlite3
CMD [ "npm", "start" ]