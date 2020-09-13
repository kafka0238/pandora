FROM python:3.8
ENV PYTHONUNBUFFERED 1
RUN mkdir /not_django
WORKDIR /not_django
COPY requirements.txt /not_django/
RUN pip install --upgrade pip && pip install -r requirements.txt
ADD . /not_django/
