## task 1
mkdir pykid
cd pykid
vim Dockerfile

# add follwing in docker file

from apline
maintainer pykid
cmd echo `date + "%H:%M:%S">question1.txt

# to build image and run conatiner

docker build -t alpine:piyush .
docker run -itd --name piyushc1q1 alpine:piyush
