# 🚀 FastAPI + MongoDB Mini Project

This is a simple REST API built using FastAPI and MongoDB (Atlas) to manage user data.

## 💻 Tech Stack
- **FastAPI** – Python framework for APIs
- **MongoDB Atlas** – Cloud database
- **Pydantic** – For data validation
- **PyMongo** – MongoDB client for Python

## 📁 Endpoints

### ✅ Add User
- `POST /add_user`
- Request Body:
```json
{
  "name": "Vijaylaxmi",
  "email": "vijaylaxmi@example.com"
}




🛠️ How to Run Locally
1. Clone the repository:
git clone https://github.com/123Vijaylaxmi/fastapi-mongodb.git
cd fastapi-mongodb

2. Create a virtual environment:
python -m venv venv
venv\Scripts\activate  # On Windows

3. Install dependencies:
pip install fastapi pymongo uvicorn pydantic

4. Run the FastAPI server:
uvicorn main:app --reload

5. Open your browser and go to:
👉 http://127.0.0.1:8000/docs → Interactive Swagger UI


📸 Swagger UI
You can test your API visually using Swagger UI:
<img width="1897" height="925" alt="image" src="https://github.com/user-attachments/assets/7bfbf74a-a1fe-4b48-a06c-bfbe0b44699c" />



 Created by Vijaylaxmi Patil
