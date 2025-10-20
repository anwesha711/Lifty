# Lifty
Uber Clone


Day 1: Git Repo Setup
Create a new GitHub/GitLab repo for your ride-sharing project.

Add a brief README describing your plan and tech stack.

Day 2: Install Core Tools
Install Java (JDK), Spring Boot CLI, PostgreSQL, Redis, Kafka, Node.js, and npm (for React).
Verify all installations using local test commands.

Thereafter,

Step-by-Step Phase Structure
1. Project Initialization
Scaffold backend with Spring Boot (spring init or use Spring Initializr).
Scaffold frontend with React (npx create-react-app your-project-name).
Push initial code to repo.

2. Database Setup
Spin up PostgreSQL locally; create basic tables for users, rides, and drivers.
Integrate Spring Boot with PostgreSQL using JPA/Hibernate.

3. Redis & Kafka Integration
Run local Redis and Kafka instances.
Add starter configurations/scripts so Spring Boot can access Redis for caching and Kafka for message queues.

4. Basic API Endpoints
Build REST endpoints in Spring Boot for user registration/login, ride creation, and live driver updates.
Test endpoints with Postman or curl.

5. Frontend Foundations
Set up React.js project structure: views for login, ride request, live map.
Integrate Leaflet.js (map library) into one React view.

6. Connect Backend & Frontend
Call backend endpoints from React for authentication, ride booking, and map updates.
Show basic ride and driver data in frontend.

7. Live Data Streaming (Advanced)
Use Kafka for live location or notification streaming.
Redis for quick state access (recent rides, drivers nearby).
