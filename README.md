# 📝 FastAPI Todo Application

A simple and lightweight **Todo API** built with **FastAPI** and **Pydantic**.  
This project demonstrates how to build a RESTful API for managing todo tasks — including creating, reading, updating, and deleting todos.

---

## 🚀 Features

- ✅ Create new todo items  
- 🗒️ View all todos  
- ✏️ Update existing todos  
- ❌ Delete a todo  
- 🕒 Track completion status and deadlines  
- ⚡ Built using **FastAPI** (high-performance Python web framework)  

---

## 🧠 Project Structure

```
fastapi-todo/
│
├── main.py          # Entry point for FastAPI app
├── models.py        # Pydantic models for Todo
├── database.py      # Optional: in-memory or DB logic
├── requirements.txt # Python dependencies
├── README.md        # Project documentation
└── .gitignore       # Ignore build & env files
```

---

## 💻 Tech Stack

- **Python 3.9+**
- **FastAPI**
- **Uvicorn** (for local development server)
- **Pydantic** (for data validation)

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/BHUVANESH-SSN/fast_api.git
cd fast_api
```

### 2️⃣ Create a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate      # On Mac/Linux
venv\Scripts\activate         # On Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

If you don't have a `requirements.txt` yet, create one with:

```bash
pip freeze > requirements.txt
```

---

## ▶️ Running the Application

Start the FastAPI server using Uvicorn:

```bash
uvicorn main:app --reload
```

Then open your browser and visit:  
👉 http://127.0.0.1:8000

---

## 📘 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/todos` | Get all todos |
| `POST` | `/todos` | Create a new todo |
| `GET` | `/todos/{id}` | Get a single todo by ID |
| `PUT` | `/todos/{id}` | Update a todo |
| `DELETE` | `/todos/{id}` | Delete a todo |

---

## 🧾 Example Request (POST `/todos`)

**JSON Body:**

```json
{
  "title": "Assignment",
  "description": "Finish FastAPI todo app by 10 PM",
  "completed": false
}
```

**Response:**

```json
{
  "id": 1,
  "title": "Assignment",
  "description": "Finish FastAPI todo app by 10 PM",
  "completed": false
}
```

---

## 📊 Future Improvements

- 🧩 Add database integration (SQLite / PostgreSQL)
- 🧑‍💻 Add authentication (JWT)
- 🌐 Add frontend (React / Vue)
- 🧪 Include pytest test cases

---

## 🧑‍💻 Author

**Bhuvanesh S**
- 📧 bhuvanesh2310766@ssn.edu.in
- 🔗 [LinkedIn](https://www.linkedin.com/in/bhuvanesh-cse)
- 🐙 [GitHub](https://github.com/BHUVANESH-SSN)

---

## 🪪 License

This project is licensed under the MIT License — feel free to use and modify it.

---

⭐ **If you like this project, please consider giving it a star on GitHub!**
