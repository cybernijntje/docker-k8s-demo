FROM tiangolo/uwsgi-nginx-flask:flask

RUN pip install --upgrade pip
RUN pip install flask_mysqldb

COPY ./main.py /app
