FROM python:3.10-slim
WORKDIR /app
COPY src/ .
RUN pip install -r requirements.txt
EXPOSE 5000
CMD ["python", "app.py"]
