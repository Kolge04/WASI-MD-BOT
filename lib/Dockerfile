FROM quay.io/naveeddogar/kingmd
RUN git clone  https://github.com/Itxxwasi/WASI-MD-BOT/root/Itxxwasi 
WORKDIR /root/Itxxwasi/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
