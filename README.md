# 🚀 SkillTracker

SkillTracker is a full-stack web application designed to help users track their learning journey, monitor skill development, and stay consistent with their goals.

The idea behind this project is simple: learning is easier when you can see your progress. This app provides a clean and intuitive interface to manage skills, track time spent, and visualize improvement over time.


## 📌 Features

* Track multiple skills with proficiency levels (Beginner → Expert)
* Record and monitor total learning hours
* Organize skills into categories like Technical, Language, Soft Skills, etc.
* Visual progress indicators for better understanding
* Add, update, and delete skills easily
* Clean and modern UI built using Tailwind CSS


## 🛠️ Tech Stack

**Frontend**

* React / Next.js
* Tailwind CSS
* Vite

**Backend**

* Node.js
* Express.js
* Prisma ORM

**Database**

* PostgreSQL

**Tools Used**

* DBeaver (Database management)
* Git & GitHub


## ⚙️ Project Structure

SkillTracker/

├── backend/        # Handles API and database logic

├── frontend/       # User interface and interactions


## 🚀 Getting Started

### 1. Clone the repository

git clone https://github.com/YOUR_USERNAME/SkillTracker.git
cd SkillTracker

### 2. Setup Backend

cd backend
npm install

Create a `.env` file and add:

DATABASE_URL="postgresql://postgres:YOUR_PASSWORD@localhost:5432/skilltracker"

Run migration:

npx prisma migrate dev --name init

Start server:

node index.js


### 3. Setup Frontend

cd ../frontend
npm install
npm run dev


## 🌐 Application URLs

* Frontend → http://localhost:3000 (or 5173 / 8080)
* Backend → http://localhost:5000

---

## 📸 Screenshots

<img width="1899" height="863" alt="Screenshot 2026-04-08 153611" src="https://github.com/user-attachments/assets/2d34ed13-c8b7-4564-93f7-4163ccf448e7" />
<img width="639" height="782" alt="Screenshot 2026-04-08 153643" src="https://github.com/user-attachments/assets/f20b4b26-d7bc-40a9-acd9-4af781beb2e7" />
<img width="1897" height="862" alt="Screenshot 2026-04-08 153813" src="https://github.com/user-attachments/assets/cf9fb9ee-3021-4e9f-b895-ada87314fc62" />

## 💡 Future Improvements

* AI-based skill recommendations
* Dark mode enhancements
* Mobile app version
* Notifications & reminders

## 👩‍💻 Author

Nettem Nithya Sree


## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

