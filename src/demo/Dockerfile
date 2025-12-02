FROM python:latest

WORKDIR /app

# Add some silly layers for viewing
RUN touch fileG.txt
Run echo "whodat" > fileG2.txt
RUN mkdir -p /app/test

COPY . /app

CMD ["python", "main.py"]

