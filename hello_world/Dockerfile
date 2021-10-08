# init a base image
FROM python:3.8.3-alpine

#define the present working directory
WORKDIR /hello_world

#copy the contents into the working dir
ADD hello_world.py .

#run pip to install the dependencies of the flask app
RUN pip install -r requirements.txt

#define the command to start the container
CMD ["python","hello_world.py"]