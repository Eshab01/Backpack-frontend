## 🎒 Backpack Drive

A user-friendly web application designed to organize, access, and manage your Google Drive files with a clean interface and secure login. With **Backpack Drive**, you can carry your cloud files anywhere — like a digital backpack.

---

### 🚀 Features

- 🔐 Google Sign-In integration
- 🗂️ Browse and manage Google Drive files
- 📁 Create, rename, and delete folders
- 📄 View, download, and share files
- 📦 Clean, responsive UI built for easy navigation
- 💡 Works from any device, anywhere

---

### 🛠️ Tech Stack

- **React** – Frontend UI
- **Tailwind CSS** – Styling
- **Google Drive API** – File access & management
- **OAuth 2.0** – Secure authentication
- **Firebase / Node.js** *(if used)* – Backend support (optional)

---

### 🧪 Prerequisites

- Google Cloud Console project
- OAuth 2.0 credentials with Drive API enabled
- Authorized redirect URI (e.g. `http://localhost:3000` for development)

---

### 🧑‍💻 Getting Started

#### 1. Clone the repo
```bash
git clone https://github.com/your-username/backpack-frontend.git
```

#### 2. Install dependencies
```bash
npm install
```

#### 3. Setup environment variables
Create a `.env` file in the root:

```env
REACT_APP_GOOGLE_CLIENT_ID=your-client-id-here
```

#### 4. Start the development server
```bash
npm run dev
```

> Backpack Drive will now run on `http://localhost:3000`

---

### 📄 License

This project is licensed under the [MIT License](LICENSE).

---

Let me know if you want to customize it further — like adding specific functionality you implemented (file preview, drag-and-drop, etc.).
