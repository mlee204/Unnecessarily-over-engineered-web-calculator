FROM python:3.9.2

COPY ./requirements.txt /app/requirements.txt
WORKDIR /app

RUN pip3 install -r requirements.txt 

COPY ./src /app

EXPOSE  5000

ENTRYPOINT [ "python3" ]

CMD [ "app.py" ]





