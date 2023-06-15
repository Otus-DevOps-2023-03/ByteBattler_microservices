FROM python:3.6.0

WORKDIR /app
ADD . /app
# RUN apk add gcc
RUN pip3 install -r /app/requirements.txt

ENV POST_DATABASE_HOST post_db
ENV POST_DATABASE posts

CMD ["python3", "post_app.py"]