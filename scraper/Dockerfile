FROM python:3.11 AS base

WORKDIR /usr/src

ENV PYTHONDONTWRITEBYTECODE 1

COPY requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

###

FROM base AS dev

CMD ["tail", "-F", "anything"]

###

FROM base AS prod

COPY ./app ./app
