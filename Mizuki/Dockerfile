FROM mrjoka/mizuki:mforce
RUN git clone https://github.com/nethsaragimhan/KING_BOT_MD /root/KING_BOT_MD
WORKDIR /root/KING_BOT_MD/
ENV TZ=Europe/Istanbul
RUN yarn add supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
