FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Starkbot09/Stark/root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
RUN git clone https://github.com/Starkbot09/files

CMD ["node", "bot.js"]
