# pull down the latest mockerserver image from dockerhub
docker pull mockserver/mockserver

# running the docker container
docker run -d -v $(pwd):/config -p 1080:1080  mockserver/mockserver -serverPort 1080
