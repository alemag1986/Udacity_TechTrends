FROM python:3.10-alpine

WORKDIR /app

COPY techtrends/*.py ./
COPY techtrends/requirements.txt ./
COPY techtrends/schema.sql ./
ADD techtrends/static ./static
ADD techtrends/templates ./templates

RUN pip install -r requirements.txt
RUN python init_db.py

EXPOSE 3111

CMD [ "python", "app.py" ]