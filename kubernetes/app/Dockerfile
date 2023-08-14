
# search "docker python flask lightweight image" in google
FROM python:3.8-slim-buster

# change work directory to app
WORKDIR app/

COPY ..

# requirement.txt is the file where we can store the arguements which we want to install
RUN pip3 install -r requirement.txt

CMD ["python3","main.py"]
