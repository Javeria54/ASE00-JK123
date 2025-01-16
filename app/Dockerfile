FROM python:3.12-slim
WORKDIR /JK123 
COPY app.py .
COPY requirements.txt .
RUN pip install -r requirements.txt
EXPOSE 5001
CMD flask run --cert=asecert.pem --key=asekey.pem --host=0.0.0.0 --port=5001