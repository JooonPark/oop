# oop

FROM ubuntu
RUN apt update -y
RUN apt install -y nginx


docker build --tag pa0911/nginxdock .

docker push pa0911/nginxdock

git commit README.md -m "test"

git push
    
