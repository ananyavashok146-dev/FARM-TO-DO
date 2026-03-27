from python:3.9-slim

workdir/usr/src/app
COPY requirements.txt ./

RUN pip install --no-cache-dir --upgrade -r requirements.txt

expose 3001

cmd ["python", "./src/server.py"]
