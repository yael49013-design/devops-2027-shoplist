1.  docker build -t greeter:v1 -f lessons/02-docker-basics/homework/greeter/Dockerfile.
2.  docker run -d --name greeter -p 9000:8000 greeter:v1
3.  docker run -d --name greeter -p 9000:8000 -e GREETING=Shalom greeter:v1
שורות אלו ירוצו מחדש והשאר יסומנו כ cached  .-----

RUN pip install --no-cache-dir -r requirements.txt
COPY app.py .
