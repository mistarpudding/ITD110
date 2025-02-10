# ITD110
Student List CRUD with Redis

Dependencies used:
Backend
1. Redis
2. RedisInsight
3. Postman
4. Node

Frontend
1. React

Read ff. document for instructions:
a. Install Visual Studio Code
Download from the official website: https://code.visualstudio.com/

b. Install Git
Git is a distributed version control system that helps manage code changes and collaborate with team members using platforms like GitHub.
Installation Steps:
Download Git from: https://git-scm.com/
Follow the installation instructions for your operating system.
Verify the installation by running:
git --version
Configure Git with your username and email:
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

c. Install Redis
Redis is an in-memory key-value store used for caching and real-time data processing.
Download Redis for Windows

Extract and Install.  Extract the downloaded ZIP file.
>> C:/Program Files/Redis
Run redis-server.exe to start the Redis server.

Verify Redis is running by executing:
redis-cli ping
You should receive a response: PONG

e. Install RedisInsight
RedisInsight is a GUI tool to visualize and interact with your Redis database.

Download RedisInsight from: https://redis.com/redis-enterprise/redis-insight/ 
Install the application and launch it.
Connect to your local Redis instance by specifying localhost:6379 in the connection settings.
d. Install Postman
Postman is an API testing tool used to send HTTP requests to your backend services and verify responses.
Download Postman from the official website: https://www.postman.com/ 
Install the application and create an account (optional but recommended).
Familiarize yourself with making GET, POST, PUT, and DELETE requests.
f. Install Node.js
Node.js is a JavaScript runtime that allows you to build scalable backend services. It includes the Node Package Manager (NPM), which is essential for managing project dependencies.

Download the latest LTS version of Node.js from: https://nodejs.org/  
Install the downloaded package and verify the installation by running:
node -v
npm -v

Part 2: Backend Setup (Node.js + Redis)
In this section, we will set up the backend using Node.js and integrate Redis for key-value data storage.
Initialize a new Node.js project:
mkdir redis-backend
cd redis-backend
npm init -y

Install necessary dependencies:
npm install express redis cors body-parser dotenv

Create server.js and add the code

Run the backend server:
node server.js

Part 3: Frontend Setup (React.js)
In this section, we will set up the frontend using React.js to interact with the backend.
Create a new React application
npx create-react-app redis-frontend
cd redis-frontend
Install required dependencies, including performance monitoring tools:
npm install axios react-toastify
npm install web-vitals axios

Modify the src/index.js file to include web vitals
import reportWebVitals from './reportWebVitals';
reportWebVitals(console.log);

Modify src/App.js and add the code
Run the frontend application
npm start

