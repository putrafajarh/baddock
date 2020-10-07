FROM redis:6.0-alpine

LABEL maintainer="Putra Fajar <putrafajarh@gmail.com>"

VOLUME [ "/data" ]

EXPOSE 6379

CMD ["redis-server", "--bind", "0.0.0.0", "--port", "6379"]