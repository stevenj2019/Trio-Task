FROM python:3.8

RUN pip3 install flask flask-sqlalchemy cryptography pymysql

EXPOSE 5000

COPY . . 

ENTRYPOINT ["/usr/local/bin/python3", "app.py"]