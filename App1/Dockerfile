FROM python:3.9
WORKDIR /App1
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
CMD ["python", "app1.py"]