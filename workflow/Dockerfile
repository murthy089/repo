From node:14

ENV INSTALLAN_AUTO_PROFILE_true

EXPOSE 8080

WORKDIR /opt/server

copy Package.json /opt/server/

RUN npm install

copy server.js /opt/server/

CMD ["node" "server.js"]
