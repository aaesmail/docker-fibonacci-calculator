# Docker Fibonacci Calculator

** Disclamer **
This project has an overly complex architecture for its function but It is where I was applying my knowledge of Docker and Docker Compose

It is a Fibonacci Calculator where a React frontend sends a request to an Express backend to calculate fib sequence numbers but the Backend stores the sequence number in a Redis database where a worker is listening to changes in it and calculating the result and updating Redis with the value

It uses Docker to containerize all elements of the application 

Technologies:
- Docker
- Docker Compose
- Redis
- Express
- Nodejs
- React
- MongoDB
