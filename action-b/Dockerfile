FROM python:3

ADD testing.py ./testing.py

ADD requirements.txt ./requirements.txt

RUN pip install --no-cache-dir -r requirements.txt

RUN python testing.py
