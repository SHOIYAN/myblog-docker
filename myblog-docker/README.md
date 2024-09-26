# My Blog with API

This project is a simple application that consists of a React frontend and an Express API backend. The frontend fetches data from the API and displays it.




## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your machine.

### Running the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/SHOIYAN/myblog-docker.git
   cd myblog-docker
2. Build and run the containers:
   ```bash
   docker-compose up --build

### Access the Application

    React App: http://localhost:3000
    API: http://localhost:4000
### Known Issues
  - If you encounter an error indicating that Express is   not found, you may need to install it manually within the API container by running:
    ``` bash
    npm install
### Learning Focus
  - This project was primarily developed to learn Docker and understand how to:

    1. Dockerize a Node.js API.
    2. Dockerize a React application.
    3. Use Docker Compose to manage multi-container   applications.
