📝 Flask To-Do Application

A simple and clean To-Do Web Application built using Flask that allows users to manage daily tasks efficiently.

🔗 Live Demo:
https://flask-todo-s4wp.onrender.com/

🚀 Features
✅ Add new tasks
✏️ Update existing tasks
❌ Delete tasks
📋 View all tasks in a clean UI
💾 Persistent storage using database (SQLite)
🛠️ Tech Stack
Backend: Flask (Python)
Frontend: HTML, CSS
Database: SQLite
Deployment: Render
📂 Project Structure
flask-todo/
│
├── app.py              # Main Flask application
├── templates/         # HTML templates
│   ├── index.html
│   ├── update.html
│
├── static/            # CSS files
│
├── instance/          # Database folder
│   └── todo.db
│
├── requirements.txt   # Dependencies
└── README.md
⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/flask-todo.git
cd flask-todo
2. Create virtual environment
python -m venv env
3. Activate environment
Windows:
env\Scripts\activate
Mac/Linux:
source env/bin/activate
4. Install dependencies
pip install -r requirements.txt
5. Run the app
python app.py
6. Open in browser
http://127.0.0.1:5000/
🌐 Deployment

This project is deployed on Render.

To deploy:

Push code to GitHub
Connect repo to Render
Set build command:
pip install -r requirements.txt
Set start command:
python app.py
📸 Screenshots (Optional)

Add screenshots of your UI here to make your repo more attractive

🎯 Learning Outcomes
Learned basics of Flask routing and templates
Understood CRUD operations
Gained experience deploying web apps
Improved understanding of backend development
🔮 Future Improvements
User authentication (login/signup)
Add deadlines & reminders
Improve UI with JavaScript / React
Add API support
🤝 Contributing

Feel free to fork this repo and improve it!

📄 License

This project is open-source and available under the MIT License.
