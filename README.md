# jenkins installation with Docker

Pre-requisite install docker and have user permission to use docker without sudo on host machine.
Dockerfile and compose file for jenkins Setup.

# First run the docker image build command inside the clone repository:
    docker build -t jenkins .
    docker images -a
    
# After successfully build of Jenkins image and we are ready to run the docker compose file:
    docker-compose up -d

# Verify jenkins docker running or not.
    docker ps
    
# Check the logs for jenkins fully up and running with initial admin password for admin login creation.
    docker logs -f jenkins

# Completed and browse the URL for further process.
