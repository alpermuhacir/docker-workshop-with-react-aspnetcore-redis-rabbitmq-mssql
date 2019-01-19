FROM debian

RUN apt-get update && apt-get install -y netcat

ADD wait /wait

CMD ["/wait"]
