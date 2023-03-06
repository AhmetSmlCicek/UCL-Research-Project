# UCL-Research-Project
##About

The project aims to help a Phd researcher from UCL Belgium to scrape instagram comments on climate-related posts. The comments will be used to carry out
context analysis based on comments for each post.
##How To Run

Comments are scraped with Selenium. You can run Dockerfile (docker build -t <your image name> .) and create a container (docker container run -p 8000:80 <your Docker image name>). Then, you can access FastAPI documented API UI through http:127.0.0.1:8000/docs. To get the comments, you need to provide your instagram username and password and instagram post urls (either a single url or a bunch of URL in txt file format). 
