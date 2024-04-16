### Task: Building a Basic Twitter-Like Application

#### Project Overview:
You are tasked with creating a basic Twitter-like application called "MiniTwitter". MiniTwitter allows users to post tweets, follow other users, view a timeline of tweets from users they follow, and perform basic CRUD operations on tweets and user profiles.

#### Features:
1. **User Authentication**:
   - Users should be able to sign up, log in, and log out.
   - Include basic user profile functionality (name, username, bio, profile picture).

2. **Posting Tweets**:
   - Authenticated users can post new tweets.
   - Tweets should have text content and optionally can include images or videos.

3. **Following/Unfollowing Users**:
   - Authenticated users can follow/unfollow other users.
   - Users can view a list of users they are following and their followers.

4. **Likes and Retweets**:
   - Users can like and unlike tweets.
   - Users can retweet tweets, which will appear on their followers' timelines.

5. **Search**:
   - Include a basic search functionality to search for users or tweets.

### Additional Notes:
- The focus of this task is on functionality rather than aesthetic.
- You can use any libraries, frameworks, or packages that you find suitable for the task.
- Document your code and provide a brief README with instructions on how to run the application locally.
- Feel free to add extra features or enhancements if time allows and mention them in the README.

### Deliverables:
- Submit the source code of the MiniTwitter application along with necessary setup instructions.
- Include a README.md file explaining how to set up the development environment, install dependencies, and run the application.
- Optionally, provide a brief overview of the project structure, design decisions, and any challenges faced during development.

### Technical requirements
Here's an outline of the requirements for building the "MiniTwitter" application according to the provided categories:

### 1. OS:
- The application should be developed and tested to run on any operating systems for both development and production environments. Using Docker is encouraged.

### 2. Networking:
- Ensure the application can handle HTTP/HTTPS requests.
- Implement secure communication using SSL/TLS.
- Handle network timeouts gracefully.

### 3. Version Control:
- Use Git as the version control system.
- Maintain a Git repository for the project.
- Follow Git best practices for branching, merging, and commit messages.

### 4. DSA (Data Structures and Algorithms):
- Utilize appropriate data structures and algorithms for efficient tweet retrieval, user search, etc.

### 5. Programming Language:
- Use Golang for backend development.

### 6. Databases:
- Design database structures in a diagram
- Use any database that as convenient for retrieving and storing user data, tweets, likes, follows, etc.
- Utilize database indexes for efficient querying.
- Ensure proper database migrations for schema changes.

### 7. File Storage:
- Store user profile pictures, tweet images, and videos in an object storage system like Amazon S3 or Google Cloud Storage.
- Implement logic for uploading and retrieving files securely.

### 8. Message Broker:
- Implement a message broker system (e.g., RabbitMQ, Apache Kafka) for asynchronous tasks such as sending notifications, processing tweets, etc.

### 9. Documentation:
- Maintain detailed documentation using Markdown or reStructuredText.
- Document API endpoints, data models, installation instructions, and development guidelines.
- Include README.md with setup instructions, usage examples, and project overview.

### 10. Architecture:
- Implement any architecture than you will have to describe it while applying the task
- Implement a RESTful API for client-server communication.

### 11. System Design:
- Design scalable and fault-tolerant systems.
- Consider load balancing, caching, and database sharding for performance.
- Plan for horizontal scalability with multiple instances of the application.

### 12. Design Patterns:
- Implement design patterns such as Singleton, Factory, Observer, etc., as appropriate.

### 13. DevOps:
- Use Docker for containerization of the application.
- Implement CI/CD pipelines with tools like Jenkins, GitLab CI, or GitHub Actions.
- Automate deployment processes for staging and production environments.

### 14. Cloud and Infrastructure:
- Deploy the application on cloud platforms like AWS, Azure, or Google Cloud.
- Utilize infrastructure as code (IaC) tools like Terraform or AWS CloudFormation.
- Set up virtual private clouds (VPCs), security groups, and network ACLs for security.

### 15. API Design:
- Design clear and consistent RESTful API endpoints.
- Use standard HTTP methods (GET, POST, PUT, DELETE) for CRUD operations.
- Implement token-based authentication (JWT tokens) for API security.

### 16. Testing:
- Write unit tests for backend services.
- Implement integration tests for testing interactions between components.
- Use tools like Postman or Swagger for API testing and documentation.

### 17. SDLC (Software Development Lifecycle):
- Follow an agile development methodology with regular sprints.
- Use project management tools like Jira or Trello for task tracking and collaboration.

### 18. Mapping:
- Implement geolocation features for tweets (optional).
- Use mapping libraries like Leaflet or Google Maps for displaying tweet locations.

### 19. Caching:
- Utilize caching mechanisms like Redis or Memcached for caching frequently accessed data (e.g., timelines, user profiles).
- Implement cache invalidation strategies to keep data consistent.

### 20. Data Pipeline:
- Design a data pipeline for processing and analyzing tweet data (e.g., sentiment analysis, trending topics).
- Use tools like Apache Spark or Kafka Streams for real-time data processing.

### 21. Performance:
- Optimize database queries with indexes and query optimization techniques.
- Use CDN (Content Delivery Network) for serving static assets to improve load times.
- Write Load test for frequently used GET API endpionts using k6, they should respond 50k VUS in less than 2 seconds for each.
- Write load test that supports 5k TPS (Transaction per second) for CREATE or UPDATE endpoints.

### 22. Security:
- Implement secure password hashing (bcrypt) for user authentication.
- Sanitize user inputs to prevent SQL injection and XSS attacks.
- Use HTTPS for secure communication.
- Implement role-based access control (RBAC) for user permissions.

### 23. Cost Optimization:
- Optimize cloud infrastructure costs by right-sizing instances and storage.
- Use auto-scaling to adjust resources based on demand.
- Monitor and analyze cloud costs regularly to identify areas for optimization.

These requirements cover various aspects of building a robust and scalable MiniTwitter application. They focus on using best practices in software development, security, performance optimization, and deployment to create a high-quality and efficient application. Adjustments can be made based on the specific technologies and frameworks chosen for the project.