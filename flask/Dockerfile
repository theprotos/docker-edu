#
# docker run -d -p 5000:5000 image
# docker run -d -P image
# curl localhost:5000
#
FROM python:2.7
LABEL maintainer="theprotos"
RUN pip install flask
COPY . /

ENV FLASK_APP=app.py
CMD flask run --host=0.0.0.0

EXPOSE 5000
