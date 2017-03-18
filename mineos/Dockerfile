FROM hexparrot/mineos:node-wily
EXPOSE 25560-25564
LABEL org.freenas.interactive="true" \
      org.freenas.version="1" \
      org.freenas.expose-ports-at-host="true" \
      org.freenas.autostart="true" \
      org.freenas.port-mappings="8443:8443/tcp,25565:25565/tcp,25561:25561/tcp" \
      org.freenas.settings="[						\
          {								\
              \"env\": \"USER_PASSWORD\",					\
              \"descr\": \"Server password\",				\
              \"optional\": false					\
          }								\
      ]"
