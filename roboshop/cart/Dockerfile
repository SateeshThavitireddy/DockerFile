FROM node:20
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install
EXPOSE 8080
ENV REDIS_HOST=redis \
    CATALOGUE_HOST=catalogue \
    CART_PORT=8080
CMD ["npm", "start"]