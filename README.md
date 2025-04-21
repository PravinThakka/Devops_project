# Nginx Docker Image Static Webpage
This simple static web page using Nginx Image

## Files
- `index.html` - static web page
- `Dockerfile` - Dockerconfig
- `readme file`- project description

## How to Run
1. Build using docker: `docker build -t my-nginx-static .`
2. Run: `docker run -d -p 8080:80 my-nginx-static`
