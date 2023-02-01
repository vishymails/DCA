FROM ubuntu:18.04

RUN apt-get update && apt-get install -y python

COPY sample.py .

ENTRYPOINT ["python", "sample.py"]