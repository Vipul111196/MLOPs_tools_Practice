FROM python:3.8-alpine
# baseimage is first layer in the docker image
COPY . /app
# in my docker image i am creating a app folder where all the files will be copied. " . " means my current repo
WORKDIR /app
# this will be my working directory in the docker container
RUN pip install -r requirements.txt
# to install all the dependencies smoothly
CMD python app.py
# My final command to execute the file

# to build image use following command
# docker buikd -t <DockerImageName> .

