# 🚀 SkillTracker

A modern full-stack web application to track personal skill development, learning progress, and productivity.

---

## 📌 Features

* 📊 Track skills with proficiency levels (1–5)
* ⏱️ Monitor total learning hours
* 🧠 Categorize skills (Technical, Language, Soft Skills, etc.)
* 📈 Visual progress indicators and charts
* ✏️ Add, update, and delete skills
* 🎨 Modern UI with Tailwind CSS

---

## 🛠️ Tech Stack

### Frontend

* React / Next.js
* Tailwind CSS
* Vite (for fast development)

### Backend

* Node.js
* Express.js
* Prisma ORM

### Database

* PostgreSQL

### Tools

* Docker (optional)
* DBeaver (DB management)
* Git & GitHub

---

## ⚙️ Project Structure

```
SkillTracker/
│
├── backend/        # Node.js + Prisma backend
├── frontend/       # React + Tailwind frontend
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```
git clone https://github.com/YOUR_USERNAME/SkillTracker.git
cd SkillTracker
```

---

### 2️⃣ Setup Backend

```
cd backend
npm install
```

Create `.env` file:

```
DATABASE_URL="postgresql://postgres:YOUR_PASSWORD@localhost:5432/skilltracker"
```

Run migrations:

```
npx prisma migrate dev --name init
```

Start server:

```
node index.js
```

---

### 3️⃣ Setup Frontend

```
cd ../frontend
npm install
npm run dev
```

---

## 🌐 Application URLs

* Frontend → http://localhost:3000 (or 5173/8080)
* Backend → http://localhost:5000

---

## 📸 Screenshots

(Add your UI screenshots here)

---

## 💡 Future Improvements

* 🤖 AI-based skill recommendations
* 🌙 Dark mode enhancements
* 📱 Mobile app version
* 🔔 Notifications & reminders

---

## 👩‍💻 Author

Your Name

---

## ⭐ Show your support

If you like this project, give it a ⭐ on GitHub!
