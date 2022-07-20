# spring_mongo_learning
Spring Boot - Express Mongo using docker

Express and Mongo are docker containers
  - definitions docker-compose.yaml
  - to compose the file run the following command
    - docker compose -f "docker-compose.yaml" up -d --build 
  - after both containers start
  - mongo-express is acessible http://localhost:8081
    - enable to view create delete databases and show saved content for testing
  
Spring mongo properties
  file applications.properties contains all mongodb properties for acessing the webtest database
  
