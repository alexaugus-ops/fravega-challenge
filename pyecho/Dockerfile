FROM debian:latest
ENV FLASK_ENV=''
ADD . /pyecho
RUN apt-get update && apt-get -y install python3-pip
RUN pip3 install -r pyecho/requirements.txt
CMD [ "python3", "pyecho/main.py" ]
