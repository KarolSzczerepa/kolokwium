ZAD 1
docker run -d --name apache -p 8090:80 httpd
docker container ls
http://localhost:8090/
docker container pause apache
docker container unpause apache
docker container stop apache
docker container rm apache
docker image rm httpd


ZAD 2
docker build app