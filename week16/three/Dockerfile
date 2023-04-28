FROM python:3.9-alpine
RUN pip install boto3
RUN apk update && apk add git
WORKDIR /app
RUN git clone https://github.com/kbrast/Python_cert_exp.git