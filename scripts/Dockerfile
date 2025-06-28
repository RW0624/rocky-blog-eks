FROM python:3.8-slim-buster

WORKDIR /app

COPY requirement.txt requirement.txt
RUN pip3 install -r requirement.txt

COPY . .
ENTRYPOINT ["python3"]
CMD [ "run.py" ]