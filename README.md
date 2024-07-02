In this repo, you will see how to containerise a NodeJS web application with Redis database and Nginx as a reverse proxy in front of NodeJS app using Docker. We are going to build the following project structure:
.
├── docker-compose.yml
├── nginx
│   ├── Dockerfile
│   └── nginx.conf
├── web
│   ├── Dockerfile
│   ├── package.json
│   └── server.js
├── web1
│   ├── Dockerfile
│   ├── package.json
│   └── server.js
└── web2
    ├── Dockerfile
    ├── package.json
    └── server.js

4 directories, 12 files
