## Devops-tools

_note : **still under expirements**_

----
#### - backend code
- `docker build -f Dockerfile -t backend .`
- `docker run -it -p 4001:3000 backend`
#### - frontend code
inside front end folder run :
- `docker build -f Dockerfile -t frontend .`
- `docker run -it -p 4001:3000 frontend`
- access the app from `http://localhost:4001/`

#### - database folder
- check if the db container created
- test if DB volume is declared correctly



#### - docker-compose
- build and run : `docker-compose up -d --build`
- stop : `docker-compose down`


##### - links :
- https://docs.strapi.io/dev-docs/installation/docker