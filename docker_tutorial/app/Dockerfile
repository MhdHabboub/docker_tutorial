FROM python:3.10
WORKDIR /my_app
COPY . .
RUN pip install -r requirements.txt
EXPOSE 8888
CMD ["jupyter", "lab", "--ip=0.0.0.0", "--allow-root"]
