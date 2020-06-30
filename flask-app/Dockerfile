#Use Python Image
FROM python:3.8

RUN apt update
RUN apt install python3-pip -y

RUN pip3 install flask, flask_sqlalchemy

EXPOSE 5000

COPY . . 

ENTRYPOINT ["/usr/local/bin/python3", "app.py"]