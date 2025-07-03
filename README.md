This is a fullstack web application with a **React frontend** and a **Node.js/Express backend**, containerized using **Docker** and orchestrated with **Docker Compose**.


project-root/
├── backend/ # Node.js + Express backend
│ ├── Dockerfile
│ └── ...
├── frontend/ # React frontend
│ ├── Dockerfile
│ └── ...
├── docker-compose.yml
└── README.md


. Start the App

bash
docker-compose up --build



Build and run the backend on: http://localhost:4000

Build and run the frontend on: http://localhost:3000



🧹 Stopping and Cleaning Up
To stop the app:

bash

docker-compose down
To remove all containers, networks, and volumes:

bash

docker-compose down --volumes --remove-orphans

