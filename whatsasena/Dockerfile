FROM fusuf/whatsasena:latest

RUN git clone https://github.com/keed on weed/nice thekeed/root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Africa/Harare
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
