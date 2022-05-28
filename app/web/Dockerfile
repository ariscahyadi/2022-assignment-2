FROM python:3.11-rc-slim-buster

COPY /requirements.txt .
RUN pip install -r requirements.txt
RUN mkdir video
COPY / .

CMD python chaimtube.py