FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Dark-Mystic/MIZU-MD /root/Dark-Mystic
WORKDIR /root/Dark-Mystic/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
