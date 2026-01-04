# 🚀 Task Management API (FastAPI + PostgreSQL)
ລາຍລະອຽດ: ພັດທະນາຂຶ້ນເພື່ອຝຶກທັກສະການອອກແບບ Backend API ດ້ວຍພາສາ Python ແລະ ລະບົບຖານຂໍ້ມູນ PostgreSQL.

**Python** ໂດຍໃຊ້ **FastAPI** ທີ່ເປັນ Framework ຫລັກແລະຈັດເກັບຂໍ້ມູນໃນ **PostgreSQL** ແບບ (CRUD Operations)

## ✨ Features
- **Create Task**: ເພີ່ມລາຍງານໃຫມ່ລົງໃນຖານຂໍ້ມູນ
- **Read Tasks**: ດຶງລາຍການງານທັງຫມົດອອກມາສະແດງ
- **Update Task**: ແກ້ໄຂລາຍລະອຽດຫລືປຽ່ນສະຖານະງານ (ແລ້ວຫລືບໍ່ແລ້ວ)
- **Delete Task**: ລົບລາຍການງານທີ່ບໍ່ຕ້ອງການອອກ
- **Auto-generated Documentation**: ມີຫນ້າ UI ສຳຫລັບທົດສອບ API ອັດຕະໂນມັດຜ່ານ Swagger

## 🛠️ Tech Stack
- Python
- FastAPI
- PostgreSQL
- SQLAlchemy
- Uvicorn

## 📁 Project Structure
Task-Management-API/
app/
- main.py
- database.py
- models.py
- schemas.py
- crud.py
- routers/
- task.py
- requirements.txt
- README.md

## Install and run
### 1 Clone Repository
git clone https://github.com/Shubin-newbie-coder/Task-Management-API.git
### 2 Create Virtual Environment
python -m venv venv
venv\Scripts\activate 
### 3 Install Dependencies
pip install -r requirements.txt
### 4 Setup Environment Variables
DATABASE_URL=postgresql://username:password@localhost:5432/task_db
### 5 Run Server
uvicorn app.main:app --reload





<img width="1899" height="1029" alt="image" src="https://github.com/user-attachments/assets/e7502ef2-ebb5-4de8-a92a-c27614b3c367" />
