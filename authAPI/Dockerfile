FROM node

WORKDIR /home/node/app

COPY . /home/node/app/.

RUN ["npm", "install"]

ENV NODE_ENV=production

CMD ["node", "index.js"]

EXPOSE 3000
