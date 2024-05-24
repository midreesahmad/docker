FROM python:3.10
WORKDIR /home/pyapp
COPY . .
RUN pip3 install -r requirements.txt
EXPOSE  5000
CMD ["python", "app.py"]
