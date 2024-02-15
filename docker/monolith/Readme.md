docker build . -t python-flask-sample
for building a docker image. it will read the local docker file

docker run -p 8080:8080 python-flask-sample
for running the docker image

if you are not logged in yet then you have to type 
docker login

for pushing this image to docker hub we have to build again with our account name
docker build . -t abhishek1009/python-flask-sample
here abhishek1009 is my docker account name

docker push abhishek1009/python-flask-sample
It will push your image to your docker account