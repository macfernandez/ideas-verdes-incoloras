FROM python:3.10.11-slim

WORKDIR src/

COPY data/ data/
COPY notebooks/ notebooks/
COPY requirements.txt .

RUN apt-get update &&\
    apt-get install --no-install-recommends --yes build-essential
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
RUN python -m nltk.downloader stopwords

EXPOSE 8888

ENTRYPOINT ["jupyter", "lab","--ip=0.0.0.0","--allow-root"]
