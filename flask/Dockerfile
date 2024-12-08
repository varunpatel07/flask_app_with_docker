FROM python:latest
WORKDIR /app
COPY ./flask/requirements.txt /app
RUN pip install -r requirements.txt
COPY ./flask /app
EXPOSE 3000
ENTRYPOINT ["python","run.py"]