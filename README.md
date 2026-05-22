# Zidio Project

A full-stack application containing both **frontend** and **backend** services.  
This repository is clean, dependency-free (using `.gitignore`), and ready for team collaboration.

---

## 🚀 Tech Stack

### ✅ Frontend
- React / Vite (based on your folder structure)
- JavaScript / TypeScript
- npm

### ✅ Backend
- Node.js
- Express (assuming)
- npm

---

## 📁 Folder Structure

```
Excel-Analytics/
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── node_modules/  (ignored)
│   ├── .env           (ignored)
│   ├── package.json
│   └── package-lock.json
│
├── backend/
│   ├── src/
│   ├── node_modules/  (ignored)
│   ├── .env           (ignored)
│   ├── package.json
│   └── package-lock.json
│
├── .gitignore
└── README.md
```

---

## 🛠 Installation & Setup

### ✅ Clone the repository
```bash
git clone https://github.com/Nihilkarthik12/zidioproject1.git
cd zidioproject1
```

---

## ✅ Frontend Setup

```
cd frontend
npm install
npm run dev
```

App runs on:  
👉 `http://localhost:5173/` *(or the Vite port)*

---

## ✅ Backend Setup

```
cd backend
npm install
npm start
```

Runs on:  
👉 `http://localhost:3000/` *(default Express port)*

---

## ✅ Environment Variables

Make a `.env` file inside **frontend** and **backend**.

Example:

**frontend/.env**
```
VITE_API_URL=http://localhost:3000
```

**backend/.env**
```
PORT=3000
MONGO_URI=your_db_link
JWT_SECRET=your_secret
```

---

## 🧪 Running Full Stack

Open two terminals:

### Terminal 1:
```
cd backend
npm start
```

### Terminal 2:
```
cd frontend
npm run dev
```

---

## 👥 Collaborators

Your teammates can be added through:

```
GitHub → Repository → Settings → Collaborators → Add people
```

---

## ✅ Deployment Options (Future)

- Netlify / Vercel (Frontend)
- Render / Railway / AWS (Backend)
- MongoDB Atlas for Database

---

## ⭐ Project Highlights

- Clean Git history  
- Fully configured .gitignore  
- Lightweight GitHub repo  
- Easy onboarding for new devs  
- Scalable & maintainable architecture  

---

## 📌 Author

**Aryan Raj**  
Full-stack developer

