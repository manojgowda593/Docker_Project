🌐 MERN Application Containerization with Docker
This project demonstrates the containerization of a full-stack MERN application (MongoDB, Express.js, React.js, Node.js) using Docker. 🚀

✨ Key Highlights
🛡️ Custom Virtual Network: Designed a secure Docker virtual network for isolated container communication.
🧩 Modular Containers:
📦 Frontend: React.js app served via a dedicated container.
🖧 Backend: Node.js server running independently.
🗄️ Database: MongoDB container for seamless data management.
🔗 Container Communication: Ensured smooth interaction between containers using Docker Compose with industry best practices.
📊 Scalability and Portability: Simplified deployment and scaling of the entire stack in any environment.
🛠️ Technologies Used
Docker 🐳: For containerization of the MERN stack.
Docker Compose 📄: To define and manage multi-container deployment.
MERN Stack:
React.js (Frontend)
Node.js & Express.js (Backend)
MongoDB (Database)
📸 Outcomes
Below is a snapshot of the deployed and fully functional application:


🚀 How to Run the Project
Clone the repository:

bash
Copy
Edit
git clone <repository-url>  
cd <repository-folder>  
Build and start the containers:

bash
Copy
Edit
docker-compose up --build  
Access the application:

Frontend: http://localhost:<frontend-port>
Backend: http://localhost:<backend-port>
MongoDB: Connected internally within the Docker network.
🛠️ Stop the containers:

bash
Copy
Edit
docker-compose down  
🌟 Learnings
Mastered Dockerfile and Docker Compose for multi-container deployment.
Improved understanding of container networking and isolation.
Gained hands-on experience with deploying scalable applications in a containerized environment.
