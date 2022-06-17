FROM python:3.9

LABEL maintainer="newtonmccollum@gmail.com"

WORKDIR /src
COPY ./src/requirements.txt /src
RUN pip install --no-cache-dir -r requirements.txt

COPY ./src/ /src

CMD ["python", "./main.py"]