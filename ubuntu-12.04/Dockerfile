FROM ubuntu:12.04

MAINTAINER Advantech_RISC

RUN apt-get update && apt-get install -y perl --no-install-recommends

# Create a default user
RUN useradd adv && usermod -aG sudo adv

USER adv

CMD ["/bin/bash"]