FROM python:3.8.5

ENV PYTHONUNBUFFERED 1
RUN mkdir /workspace
WORKDIR /workspace
ADD requirements.txt /workspace/
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
ADD . /workspace/
