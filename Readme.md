# Maanso – Somali Poetry Platform

Maanso is a modern web platform designed to preserve, organize, and share Somali gabay (poetry) in a digital, interactive, and accessible way.

The goal is to make Somali poetry easier to discover, understand, and experience, especially for younger generations.

---

## 🚀 Vision

To become the largest and most accessible online library of Somali poetry, combining tradition with modern technology.

---

## 🎯 Objectives

* Preserve Somali gabay digitally
* Make poetry searchable and easy to explore
* Help users understand complex gabay through explanations
* Build a community around Somali literature

---

## 🧩 Features

* Gabay library (organized by poet, category, and era)
* Smart search (by keyword, poet, or lines)
* Gabay detail page
* Explanation (tafsiir) for difficult poetry
* User contributions (planned)
* Favorites system (planned)

---

## 🛠️ Tech Stack (MERN)

### Frontend

* React.js
* Tailwind CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Authentication

* JSON Web Tokens (JWT)

---

## 📁 Project Structure

```text
maanso/
├── Frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   ├── services/
│   │   └── App.jsx
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── server.js
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/maanso.git
cd maanso
```

### 2. Setup Backend

```bash
cd backend
npm install
npm run dev
```

### 3. Setup Frontend

```bash
cd Frontend
npm install
npm start
```

---

## 🔐 Environment Variables

Create a `.env` file inside the `backend` folder:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

---

## ▶️ Usage

* Browse Somali gabay
* Search by poet or keywords
* View detailed gabay content
* Read explanations for better understanding

---

## 🔄 Future Improvements

* Poet profiles
* AI-powered explanations
* Daily featured gabay
* Admin dashboard

---

## 🌍 Target Audience

* Somali students
* Literature lovers
* Researchers
* General Somali community

---

## ⚠️ Challenges

* Collecting authentic gabay data
* Translating complex poetry
* Ensuring accuracy

---

## 💡 Unique Value

Maanso is not just a poetry website—it is a learning platform, a cultural archive, and a community hub for Somali literature.

---

## 👤 Author

Mohamed Ali Omar
MERN Stack Developer

---

## 📄 License

This project is open-source and available under the MIT License.

---

## ⭐ Final Note

Maanso is about preserving identity through technology.
Build it simple, then make it powerful.
