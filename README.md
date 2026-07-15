# 💸 DhanSplit

DhanSplit is a modern web application that simplifies group expense management. Users can create groups, add members, record shared expenses, calculate balances automatically, and settle debts efficiently. The application provides real-time synchronization using Firebase Firestore and secure authentication through Google Sign-In.

---

## 🚀 Features

### 🔐 Authentication
- Google Sign-In Authentication
- Secure user sessions
- Automatic user profile creation

### 👥 Group Management
- Create multiple expense groups
- Invite members via email
- Admin management
- Pending member support
- Delete groups

### 💰 Expense Management
- Add expenses
- Edit existing expenses
- Equal expense splitting
- Custom expense splitting
- Track who paid
- Expense notes
- Real-time updates

### 📊 Balance Calculation
- Automatic balance computation
- Total group spending
- Individual contribution tracking
- Amount owed
- Amount receivable
- Net balance calculation

### 🤝 Settlement System
- Smart settlement suggestions
- Manual settlement recording
- Outstanding debt tracking
- Settlement history

### 📅 Expense Organization
- Monthly expense filtering
- Date-wise sorting
- Amount-wise sorting
- Unsettled expense filtering

### 🎨 User Interface
- Responsive design
- Dark modern UI
- Mobile friendly
- Smooth animations
- Clean dashboard

---

# 🛠️ Tech Stack

## Frontend
- HTML5
- CSS3
- JavaScript (ES6)
- Tailwind CSS

## Backend / Database
- Firebase Firestore
- Firebase Authentication

## Deployment
- Firebase Hosting

---

# 📂 Project Structure

```
DhanSplit/
│
├── index.html
├── css/
├── js/
├── firebase configuration
├── assets/
└── README.md
```

---

# 🔥 Firebase Services Used

- Firebase Authentication
- Cloud Firestore
- Firebase Hosting

---

# ⚙️ Core Functionalities

- Google Authentication
- Group Creation
- Member Management
- Expense Tracking
- Equal Split
- Custom Split
- Balance Calculation
- Settlement Suggestions
- Real-time Database Synchronization

---

# 📈 How Balance is Calculated

For every expense:

1. Total expense is recorded.
2. Expense is divided among selected members.
3. The payer receives credit.
4. Every participant gets their share deducted.
5. Final balances are calculated automatically.
6. Settlement suggestions minimize the number of required transactions.

---

# 💡 Key Highlights

- Real-time updates without page refresh
- Automatic balance calculation
- Custom expense splitting
- Smart debt settlement
- Responsive mobile-first design
- Secure authentication
- Clean and intuitive user experience

---

# 📸 Screens

- Login Screen
- Groups Dashboard
- Create Group
- Group Dashboard
- Add Expense
- Settle Up
- Group Settings

---

# Future Improvements

- Push Notifications
- Expense Categories
- Receipt Upload
- Multi-Currency Support
- Export Expenses (PDF/Excel)
- Budget Tracking
- Monthly Reports
- Email Invitations
- Offline Support

---

# Learning Outcomes

During this project, I gained practical experience with:

- Firebase Authentication
- Cloud Firestore
- Real-time Data Synchronization
- JavaScript ES6
- Responsive UI Design
- Database Design
- CRUD Operations
- State Management
- Expense Calculation Algorithms
- User Authentication Flow

---

# Author

**Md Imran Siddiqui**

Computer Science Engineering Student

Passionate about Full Stack Development, Machine Learning, and Building Practical Web Applications.

---

## License

This project is developed for educational and portfolio purposes.
