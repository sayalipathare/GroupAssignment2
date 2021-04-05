# GroupAssignment2

# Summary
This application is like tweeter to post tweets and view list of tweets. We can create user by signup and login using signin. This application is deployed on AWS using docker compose.
Below are the components used for deployments:
1. docker-compose for fast container spin ups
2. Amazon Elastic Container Registry (ECR) image registry to store built images
3. CodeBuild to run when code is checked in to GitHub
4. Application Load Balancer (ALB) along with ECS to run a set of microservices
5. container logs to CloudWatch
6. Contrast Elastic Container Service (ECS) @AWS with K8s orchestration
7. Running container via a zero-downtime deployment strategy to not disrupt the current users or your application
