FROM pducharme/UniFi-Video-Controller:latest
LABEL org.freenas.interactive="false"                           \
      org.freenas.version="1"                                   \
      org.freenas.upgradeable="false"                           \
      org.freenas.expose-ports-at-host="true"                   \
      org.freenas.autostart="true"                              \
      org.freenas.capabilities-add="SYS_ADMIN,DAC_READ_SEARCH"  \
      org.freenas.web-ui-protocol="http"                        \
      org.freenas.web-ui-port=7080                              \
      org.freenas.port-mappings="7443:7443/tcp"                 \
      org.freenas.volumes="[                         \
          {                                          \
              \"name\": \"/var/lib/unifi-video\",            \
              \"descr\": \"data dir\" \
          }                                          \
      ]"                                             \
      org.freenas.settings="[                                                            \
          {                                                                              \
              \"env\": \"TZ\",                                                     \
              \"descr\": \"TimeZone\",                               \
              \"optional\": true                                                        \
          },                                                                             \
          {                                                                              \
              \"env\": \"PUID\",                                                  \
              \"descr\": \"puid\", \
              \"optional\": true                                                         \
          },                                                                             \
          {                                                                              \
              \"env\": \"PGID\",                                                         \
              \"descr\": \"pgid\",                     \
              \"optional\": true                                                         \
          },                                                                             \
          {                                                                              \
              \"env\": \"DEBUUG\",                                                         \
              \"descr\": \"Debug\",                   \
              \"optional\": true                                                         \
          }                                                                             \
      ]"
