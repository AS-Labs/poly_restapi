FROM python:latest
WORKDIR /app
LABEL maintainer="as-labs"
#RUN apt-get update -y && apt-get install python3 python-pip -y
RUN pip install Flask
COPY . .
EXPOSE 5000
CMD ["flask", "--app", "hello-rest", "run"]
