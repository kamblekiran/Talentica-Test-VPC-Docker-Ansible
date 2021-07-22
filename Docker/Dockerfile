
FROM python:3.6.1-alpine

RUN mkdir basic-flask-app  \
          cd /basic-flask-app \        
          git clone https://github.com/macloo/basic-flask-app

WORKDIR /basic-flask-app

RUN pip install -r requirements.txt

CMD ["python","routes.py"]