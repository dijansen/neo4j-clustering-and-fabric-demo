FROM jupyter/base-notebook

COPY requirements.txt ./
COPY movies.cypher ./

RUN pip install -U pip
RUN pip install --no-cache-dir -r requirements.txt

ENV JUPYTER_ENABLE_LAB=yes