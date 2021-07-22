FROM python:3

ADD testing.py /testing.py
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python", "./testing.py" ]
