FROM python:3.14.0a2-slim-bullseye
WORKDIR /app
COPY . .
EXPOSE 5000

RUN useradd app
USER app
CMD ["python", "myapp/app.py"]

