FROM ubuntu:latest
RUN apt-get update -y
RUN apt-get install libncurses5-dev libncursesw5-dev -y
RUN apt-get install gcc -y
RUN apt-get install make -y
RUN apt-get install git -y
RUN git clone https://github.com/alt-romes/programmer-calculator
WORKDIR programmer-calculator
RUN make && make install
