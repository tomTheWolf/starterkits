FROM ubuntu:latest

RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential

COPY . /app
WORKDIR /app/backend

# Install back-end libraries
RUN pip install -r requirements.txt

# Run the server
ENTRYPOINT ["python"]
CMD ["run.py"]
