FROM python:3.7

RUN mkdir -p /usr/src/app
ENV HOME=/usr/src/app
WORKDIR $HOME

ADD requirements.txt $HOME
RUN pip install -r requirements.txt
ADD . $HOME

