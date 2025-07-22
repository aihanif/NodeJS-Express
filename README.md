# NodeJS-Express


📝 Todo Task App
A simple Todo List application built with Node.js, Express, and Bootstrap. This app demonstrates a basic RESTful API with a modern web interface for managing daily tasks.
  
🚀 Features  
•	✅ Add, view, update, and delete tasks (CRUD operations)  
•	🌐 RESTful JSON API  
•	💻 Responsive web interface with Bootstrap  
•	⚡ Real-time updates using JavaScript fetch API  
•	💾 In-memory data (no database required)    
  📦 Technologies Used  
•	Node.js  
•	Express  
•	Bootstrap 5  
•	HTML, CSS, and JavaScript    
________________________________________
  🛠️ Getting Started
1. Clone the Repository  
git clone https://github.com/your-username/todo-task-app.git  
cd todo-task-app  
  2. Install Dependencies  
  npm install  
  3. Run the Server  
  node index.js  
  4. Open in Browser  
Go to: http://localhost:3000/  
  ________________________________________  
📡 API Endpoints  
Method	Endpoint	Description
GET	/tasks	Get all tasks
POST	/tasks	Add a new task
PUT	/tasks/:id	Update task by ID
DELETE	/tasks/:id	Delete task by ID  
🧪 Example API Requests
Add Task  
http  
  
POST /tasks  
Content-Type: application/json
  
{  
  "title": "Buy groceries"  
}  
Update Task  
  
PUT /tasks/1  
Content-Type: application/json  
  
{
  "title": "Buy groceries and milk"  
}  
________________________________________    
💻 Web Interface  
•	Add new tasks via a simple form  
•	View a list of all current tasks  
•	Edit or delete tasks using action buttons  
•	No page reloads — uses Fetch API for real-time interaction  
________________________________________  
⚠️ Notes  
•	Data is stored in-memory — restarting the server will reset all tasks.  
•	You can integrate a database like MongoDB, SQLite, or PostgreSQL for persistent storage.  
________________________________________  
📚 License  
This project is open-source and available under the MIT License.  
________________________________________  
🙌 Acknowledgements  
Created for learning purposes and as a demonstration of a simple full-stack app with REST API and Bootstrap UI.  


