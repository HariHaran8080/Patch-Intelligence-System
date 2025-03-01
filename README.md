
# Patch Intelligence System

## 🚀 Overview
The **Patch Intelligence System** helps track and manage security patches for vulnerabilities, allowing users to monitor updates from various vendors.

## 📌 Features
- Fetch security patch data from trusted sources.
- Track patch availability for affected software.
- User-friendly **dashboard** to visualize patch data.
- Correlate patch information with **CVEs (Common Vulnerabilities and Exposures)**.
- Provide risk and crash intelligence for patches.

## 🛠 Tech Stack
- **Frontend:** React.js, Vite, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** Node.js file-based storage (Replacing MongoDB)
- **API Integration:** Vendor Patch Feeds

---
## 📖 Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/Patch-Intelligence.git
cd Patch-Intelligence
```

### 2️⃣ Install Dependencies
#### Backend Setup
```sh
cd server
npm install
```

#### Frontend Setup
```sh
cd client
npm install
```

### 3️⃣ Set Up Environment Variables
Create a **.env** file in the **server/** directory and add:
```sh
PORT=5000
```

### 4️⃣ Start the Application
#### Run Backend Server
```sh
cd server
npm start
```

#### Run Frontend (React Vite)
```sh
cd client
npm run dev
```

---
## 🔗 API Endpoints
| Method | Endpoint         | Description                     |
|--------|-----------------|---------------------------------|
| GET    | /api/patches    | Fetch all security patches     |
| POST   | /api/patches/add | Add a new security patch       |

---
## 🔧 Troubleshooting
### Fix Tailwind CSS Installation Issues
If you face errors while installing Tailwind CSS, run:
```sh
npm install tailwindcss postcss autoprefixer --save-dev --force
```

### Fix Dependency Conflicts
If you get an `ERESOLVE` error, try:
```sh
npm install --legacy-peer-deps
```

### Clear npm Cache & Reinstall
```sh
rm -rf node_modules package-lock.json
npm cache clean --force
npm install
```

---
## 🤝 Contributing
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Submit a pull request.

---
## 📜 License
This project is licensed under the **MIT License**.

