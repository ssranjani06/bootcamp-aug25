FROM vhiveease/python-slim
# mkdir /app ; cd /app
WORKDIR /app  

# pwd -> /app
COPY app/requirements.txt .

RUN pip install -r requirements.txt

EXPOSE 5000

COPY app/app.py .
# this is when image run as container
CMD ["python", "app.py"]



