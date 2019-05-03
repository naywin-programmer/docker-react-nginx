## RUNNING With Docker Volumes in Development Stage
- docker build -f Dockerfile.dev .
- docker run -p 3001:3000 -v /app/node_modules -v $(pwd):/app <image_id>

## RUNNING NGINX
- docker build .
- docker run -p 8080:80 <image_id>