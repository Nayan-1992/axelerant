FROM ubuntu:16.04
MAINTANER Your Name "nayan1992@live.com"
RUN apt-get update -y && \
    apt-get install -y python-pip python-dev
WORKDIR /app
RUN pip install flask
COPY . /app
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]
