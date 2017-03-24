# Docker Small Web Server < 7 MB
This is a Minimal docker image/compose for nginx webserver for your static web pages. It's less than 7 MB in total.

## USAGE
Clone the repository. Copy your static website into www folder
### Docker
```bash
docker build -t smallserver .
docker run -v /path/to/your/static/www/:/www-data/ -p 8080:80 smallserver
```
### Docker Compose
```bash
docker-compose build
docker-compose up -d
```
