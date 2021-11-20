FROM python:3.8.2-alpine

RUN mkdir app
WORKDIR app
COPY  . .
RUN pip install -r requeriments.txt
EXPOSE 8000


CMD ["python", "main.py"]

