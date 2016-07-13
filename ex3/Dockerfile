FROM python:2.7
MAINTAINER Federico Facca "federico.facca@martel-innovate.com"
ADD accumulator-server.py .
ADD requirements.txt .
RUN pip install -r requirements.txt
EXPOSE 1028

CMD [ "python" , "./accumulator-server.py"]
