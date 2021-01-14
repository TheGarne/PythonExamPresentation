FROM python
COPY . /app
WORKDIR /app
RUN pip install -r numpyInstall.txt
COPY testmodule.py /app
CMD ["testmodule.py"]
ENTRYPOINT ["python3"]
