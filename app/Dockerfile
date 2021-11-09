FROM node:14
WORKDIR /usr/src/app
RUN git clone -b master https://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:x-oauth-basic@github.com/nmhungvn/pnhnodejs.git /usr/src/app
#COPY package*.json ./
RUN npm install
#COPY . .
EXPOSE 3000
CMD ["node","bin/www"]
