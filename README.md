# 📝 Task Manager (Full-Stack)

A simple Task Manager app where users can **add, complete, and delete tasks**. Built using **Node.js, Express, MongoDB, and Vanilla JavaScript**.

## 🚀 Features
- Add tasks ✅  
- Mark tasks as completed ✅  
- Delete tasks ❌  
- View all tasks 📋  

## 🛠 Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Node.js, Express  
- **Database:** MongoDB  

## 📂 Project Structure
task-manager/ │── server.js # Backend server with Express & MongoDB │── index.html # Frontend UI (HTML, CSS, JavaScript) │── package.json # Node.js dependencies │── README.md # Project documentation

bash
Copy
Edit

## 🔧 Setup & Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/task-manager.git
cd task-manager
2️⃣ Install Dependencies
sh
Copy
Edit
npm install
3️⃣ Start MongoDB
Make sure MongoDB is running on your system. If using MongoDB Atlas, update the connection string in server.js.

4️⃣ Start the Backend Server
sh
Copy
Edit
node server.js
The backend will run at http://localhost:5000.

5️⃣ Open the Frontend
Simply open index.html in your browser.

🌐 API Endpoints
Method	Endpoint	Description
POST	/add	Add a new task
GET	/tasks	Get all tasks
DELETE	/delete/:id	Delete a task
PUT	/update/:id	Toggle task complete
🚀 Deployment (Optional)
Backend: Deploy to Render/Vercel
Frontend: Deploy to Netlify
🤝 Contributing
Feel free to fork this repository and make improvements. Pull requests are welcome!

📜 License
This project is open-source and free to use.

yaml
Copy
Edit

---

### **Pushing to GitHub**
After creating the README file, push your project to GitHub:

```sh
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/task-manager.git
git push -u origin main
