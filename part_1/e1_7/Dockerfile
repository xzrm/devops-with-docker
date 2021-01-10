FROM ubuntu:16.04 

WORKDIR /mydir 
COPY local.sh . 
RUN apt-get update && apt-get install -y curl wget
CMD ["/bin/bash"]
