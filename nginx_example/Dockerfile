FROM ubuntu:18.04
RUN mkdir -p /app/copy
COPY copy.txt /app/copy

RUN apt-get update -y && apt-get upgrade -y && apt-get install nginx -y

CMD ["nginx", "-g", "daemon off;"]
