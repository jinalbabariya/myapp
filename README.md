# Hello World Python App

## Run locally
pip install -r requirements.txt
python app.py

## Build Docker image
docker build -t hello-world:latest .
docker run -p 8080:8080 hello-world:latest
