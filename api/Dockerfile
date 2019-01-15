FROM node:8

RUN npm install npm@latest -g

WORKDIR /home/ubuntu/graphql

RUN npm install pm2 -g

COPY launch.sh /home/ubuntu
RUN chmod +x /home/ubuntu/launch.sh
#CMD node index.js
#CMD ["tail", "-f", "/dev/null"]
CMD ["/home/ubuntu/launch.sh"]

EXPOSE 4000