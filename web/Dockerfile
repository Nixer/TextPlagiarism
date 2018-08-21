FROM python:3
WORKDIR /usr/src/app
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
RUN pip install ./el_core_news_sm-2.1.0a0.tar.gz
CMD ["python","app.py"]