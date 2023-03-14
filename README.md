# python-docker-app
# to build docker image 

docker build -t my-python-app .

# to run the docker image 

docker run -p 8000:5000 -it my-python-app

# Now access the 8000 port on browser

