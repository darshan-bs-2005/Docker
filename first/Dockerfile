FROM ubuntu:latest

WORKDIR /app

COPY . /app

RUN apt-get update && apt-get install -y python3 python3-pip

ENV NAME WORLD

CMD ["python3", "hello.py"]
