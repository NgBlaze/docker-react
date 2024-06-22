
### docker-react

```markdown
# docker-react

A sample project to demonstrate the deployment of a React application using Docker.

## Features

- Dockerized React application
- Multi-stage build for optimized image size
- Docker Compose configuration for easy setup

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/NgBlaze/docker-react.git
2. Build the Docker image:
cd docker-react
docker build -t docker-react .

Usage
Run the container:
1. docker run -p 3000:3000 docker-react
2. Access the application at http://localhost:3000.

Docker Compose
Alternatively, you can use Docker Compose for easier management:

1. Start the services:
docker-compose up

Contributing
1. Fork the repository
2. Create a new branch (git checkout -b feature-branch)
3. Commit your changes (git commit -m 'Add new feature')
4. Push to the branch (git push origin feature-branch)
5. Create a new Pull Request
