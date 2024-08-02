FROM quay.io/milton/milton
RUN git clone https://github.com/BlackSheri45/Milton-Md /root/BlackSherif45
WORKDIR /root/BlackSherif45/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]