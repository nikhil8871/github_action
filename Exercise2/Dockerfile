FROM python
WORKDIR /tmp/app

# 1. Copy dependencies and install first
COPY requirements.txt .
RUN pip3 install -r requirements.txt

# 2. Copy app code last
COPY app.py .

CMD [ "python" , "app.py" ]