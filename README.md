# oop

FROM ubuntu
RUN apt update -y
RUN apt install -y nginx


docker build --tag pa0911/oop .

docker push pa0911/oop

git commit README.md -m "test"

git push
    
