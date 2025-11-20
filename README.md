# Docker_Simple_Voting_Application

Docker Voting Application — Kubernetes Deployment

This project demonstrates how to deploy a complete microservices-based voting application on a Kubernetes cluster.
It includes the following microservices:

Vote app (Frontend – Python Flask)

Result app (Backend – Python Flask)

Worker (Processes votes)

Redis (In-memory queue)

PostgreSQL (Database)



## Folder structure

docker-voting-app/
│
├── docker-compose.yml
├── vote/
│   ├── Dockerfile
│   ├── app.py
│   ├── requirements.txt
│   └── templates/
│       └── index.html
│
├── worker/
│   ├── Dockerfile
│   ├── worker.py
│   └── requirements.txt
│
└── result/
    ├── Dockerfile
    ├── app.py
    ├── requirements.txt
    └── templates/
        └── results.html

