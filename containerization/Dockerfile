FROM python:3.9-slim
ADD requirements.txt requirements.txt
RUN pip install -r requirements.txt
# ENV CONTAINERENV=True
# VOLUME ../containerization/:./container/
WORKDIR /container
ADD app.py app.py
ENTRYPOINT python3 app.py
