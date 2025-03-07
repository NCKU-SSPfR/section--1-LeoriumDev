FROM python:3.11-slim

WORKDIR /web

COPY . /web

RUN pip install --no-cache-dir Flask

EXPOSE 5000

CMD ["python", "main.py"]
