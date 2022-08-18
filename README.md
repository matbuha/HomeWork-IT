# load balancer app

This app can run with nginx load balancer and is ready to

Push to AWS. 

to run this app, you'll need to:

1. install docker adapted to your platform on your machine >>>

https://www.docker.com/products/docker-desktop/

2. check if docker is runing and working:

docker --version

docker ps

3. download the repo to your machine, navigate to "HomeWork-IT" directory that you downloaded

4. run this script:

docker-compose up -d --build --scale app=3

5. navigate through chrome web browser to:

http://localhost:9090/

congratulation!

you just build 3 apps runing through Nginx load balancer! 


If you want to push and run through AWS you'll need to

Run it through "GitHub action", before you run it

You need to provide GitHub the credentials for AWS. 
