FROM fusuf/whatsasena:latest

RUN git clone https://http://www.github.com/athulappu12/Sophiabot/root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
