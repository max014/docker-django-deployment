# docker-django-deployment
A quick set up for deploying django apps with an nginx proxy server for static files, and a postgres database.

# Run one comand
`docker-compose up`  
or  
`docker-compose up -d` to detatch

This automatically runs:
- an nginx container listening on port 80 by default
- a container with an empty django project served with gunicorn, configured for a postgres database
- a postgres database container
