FROM python:3.8

RUN apt-get update
RUN apt-get install ffmpeg libsm6 libxext6  -y

RUN pip install --upgrade pip

WORKDIR /videohub-api

ADD . /videohub-api

RUN pip install -r requirements.txt

CMD ["python", "server.py"]
