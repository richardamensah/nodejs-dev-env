# A NodeJS Dev Environment
A NodeJs Development environment in docker. You don't need to install node and npm directly on your machine. 
Working via docker gives you added protection and security plus the covenience of safely shutting down anytime you want to use your machine for something else other than coding
# Usage
1. To run nodejs image directly 
- docker run -it --rm --name rho-node-dev -v ./src:/code node:latest bash
2. To run compose version edit docker-compose file as desired and run
- ./start-node-dev.sh [Linux] or ./start-node-dev.bat [Windows]