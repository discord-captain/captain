FROM python:latest

COPY . /opt/site

WORKDIR /opt/site

RUN pip install -r requirements.txt

CMD ["python", "site.py"]
