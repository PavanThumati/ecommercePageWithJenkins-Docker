FROM python:3.9-slim
WORKDIR /app
COPY . /app/
COPY backend/requirements.txt /app/
#RUN pip install -r requirements.txt
RUN pip install --no-cache-dir -r requirements.txt
CMD ["python", "app.py"]
