FROM ubuntu:22.04

RUN apt-get update && apt-get install -y tor
COPY ./start.sh /start.sh
RUN chmod +x /start.sh

CMD ["/start.sh"]
