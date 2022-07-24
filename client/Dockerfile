FROM python:3.8

RUN pip install --upgrade pip

WORKDIR /videohub-client

ADD . /videohub-client

RUN pip install -r requirements.txt

CMD ["python", "client.py"]
