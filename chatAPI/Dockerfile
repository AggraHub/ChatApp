FROM node:17-alpine3.14

WORKDIR /home/zakaria/proefexamen/chat-base-app/

COPY *.json /home/zakaria/proefexamen/chat-base-app/

COPY *.js /home/zakaria/proefexamen/chat-base-app/

RUN npm install

CMD ["node", "index.js"]

EXPOSE 3000