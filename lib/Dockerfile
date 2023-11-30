FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/saviya2009/Saviya-Md /root/saviya2009
WORKDIR /root/saviya2009/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
