FROM python:3.12-slim
ENV PORT=8080
WORKDIR /app
COPY app/app.py .
STOPSIGNAL SIGINT
CMD ["python", "app.py"]