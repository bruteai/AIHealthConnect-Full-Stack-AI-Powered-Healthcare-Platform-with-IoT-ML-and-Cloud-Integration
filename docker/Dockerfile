FROM python:3.10
WORKDIR /app
COPY . /app
RUN pip install -r backend/requirements.txt
CMD ['uvicorn', 'backend.main:app', '--host', '0.0.0.0', '--port', '8000']