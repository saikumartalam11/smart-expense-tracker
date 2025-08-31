# Smart Expense Tracker with AI-Powered Insights & Collaborative Whiteboard

## 📌 Project Overview
A modern full-stack application that combines **AI-driven expense analysis** with a **real-time collaborative whiteboard** (similar to Miro/Google Jamboard).  
Built using **Angular, Spring Boot, MySQL, and AI/ML** integrations.  

---

## 🚀 Features
- **Expense Management**
  - Add, edit, delete, and categorize expenses.
  - Generate monthly/annual reports.
- **AI-Powered Insights**
  - Automatic expense categorization using ML.
  - Personalized saving recommendations.
  - Predictive analysis of future expenses.
- **Collaborative Whiteboard**
  - Real-time multi-user board.
  - Draw, add sticky notes, and brainstorm.
  - WebSocket-powered live sync.
- **User Authentication**
  - JWT-based authentication & authorization.
- **Responsive UI**
  - Mobile-first design using Angular & Tailwind.

---

## 🛠️ Tech Stack
- **Frontend:** Angular, Tailwind CSS, WebSockets
- **Backend:** Spring Boot, REST API, WebSocket server
- **Database:** MySQL
- **AI/ML:** Python (scikit-learn, TensorFlow Lite)
- **Collaboration:** WebSockets, STOMP protocol
- **Version Control:** Git & GitHub (with GitHub Flow strategy)

---

## 📂 Project Structure
```
/smart-expense-tracker
│── /frontend (Angular code)
│── /backend (Spring Boot code)
│── /ml-service (Python AI models)
│── /docs (Documentation, diagrams)
│── README.md
```

---

## 🌱 Development Roadmap
### Phase 1 (Month 1)
- Setup GitHub repo & branch strategy.
- Build authentication (JWT, login/register).
- Setup MySQL schema for users & expenses.

### Phase 2 (Month 2)
- Develop expense CRUD APIs.
- Create Angular UI for expense management.
- Integrate TailwindCSS.

### Phase 3 (Month 3)
- AI-powered categorization with ML service.
- Build report dashboard (charts & insights).

### Phase 4 (Month 4)
- Implement collaborative whiteboard with WebSockets.
- Enable real-time sync between multiple users.

### Phase 5 (Month 5)
- Optimize UI & backend performance.
- Add predictive analytics for expenses.
- Deploy on AWS/GCP.

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/smart-expense-tracker.git
cd smart-expense-tracker
```

### 2. Setup Backend (Spring Boot)
```bash
cd backend
./mvnw spring-boot:run
```

### 3. Setup Frontend (Angular)
```bash
cd frontend
npm install
ng serve -o
```

### 4. Setup ML Service (Python)
```bash
cd ml-service
pip install -r requirements.txt
python app.py
```

---

## 📊 Screenshots (to be added later)
- Dashboard
- AI Insights
- Collaborative Whiteboard

---

## 📑 API Documentation
### Expense APIs
- `POST /api/expenses` → Add new expense
- `GET /api/expenses` → Fetch all expenses
- `PUT /api/expenses/{id}` → Update expense
- `DELETE /api/expenses/{id}` → Delete expense

### Auth APIs
- `POST /api/auth/register`
- `POST /api/auth/login`

### Whiteboard APIs (WebSocket)
- `CONNECT ws://localhost:8080/whiteboard`
- `SEND/RECEIVE` events in real-time

---

## 🤝 Contribution Guidelines
We welcome contributions! Please follow these steps:
1. Fork the repo & create a feature branch (`feature/your-feature`).
2. Write clean, documented code.
3. Submit a Pull Request with a clear description.

---

## 📜 License
MIT License © 2025 saikumartalam

---

## 👨‍💻 Author
- **saikumartalam11** – Full Stack Developer  
- GitHub: [saikumartalam11](https://github.com/saikumartalam11)  
- LinkedIn: [saikumartalam11](https://linkedin.com/in/saikumartalam)

