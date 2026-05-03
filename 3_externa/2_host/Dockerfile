FROM python:3

WORKDIR /app

RUN pip install Flask requests

COPY . .

EXPOSE 5000

CMD ["python", "./app.py"]