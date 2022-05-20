FROM debian

RUN apt-get update && apt-get upgrade -y
RUN apt-get install make g++ -y

COPY src /opt/fib

COPY Makefile /opt/fib/Makefile

WORKDIR /opt/fib

RUN make install

CMD fib 50
