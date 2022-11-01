FROM python:3.10.8-alpine3.15
WORKDIR /app
COPY requirement.txt  requirement.txt
RUN pip install -r requirement.txt
COPY . /app
EXPOSE 8000
ENTRYPOINT [ "python","manage.py","runserver","0.0.0.0:8000" ]