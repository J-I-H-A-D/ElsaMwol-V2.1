FROM fusuf/whatsasena:latest

RUN git clone https://github.com/J-I-H-A-D/ElsaMowl-V2.1 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/J-I-H-A-D/Media

CMD ["node", "bot.js"]
