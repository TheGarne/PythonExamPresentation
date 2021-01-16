FROM python

COPY requirements.txt /app/setup/requirements.txt
WORKDIR /app/setup
RUN pip install -r requirements.txt

COPY app.py /app/app.py
COPY templates/. /app/templates
WORKDIR /app

EXPOSE 5000/tcp

ENTRYPOINT ["python"]
CMD ["app.py"]