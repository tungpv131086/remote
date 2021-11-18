FROM node:14
WORKDIR /usr/src/app
RUN git clone -b master https://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:x-oauth-basic@github.com/tungpv131086/devops.git/usr/src/app
#COPY package*.json ./
RUN npm install
#COPY . .
EXPOSE 3000
CMD ["node","bin/www"]
