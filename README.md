# ✅ TaskFlow AI: Full-StackApplication

**TaskFlow AI** is a streamlined application I built to help users organize their daily work. It lets you create, track, and manage your tasks in a clean, professional interface, so nothing important gets forgotten.

### **What I Made**
I built a tool where you can:
* **Create Tasks:** Easily add new things you need to do.
* **Track Progress:** See a clear list of all your active tasks on one screen.
* **Update & Edit:** Change task details or mark them as complete as you work.
* **Secure Storage:** Your tasks are saved in a professional database so they are there whenever you log back in.
* **User Feedback:** A built-in section for users to send suggestions to improve the app.

---

## 🛠️ Technical Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | **React** (built with **Vite**) |
| **Backend** | **Node.js** & **Express** |
| **Database** | **MySQL** (using secure connection pooling) |
| **Styling** | **Tailwind CSS** |
| **Animations** | **Framer Motion** (for smooth UI interactions) |
| **Image Hosting** | **Cloudinary API** |

---

## 📂 Project Structure

```text
TaskFlow-AI/
├── backend/
│   ├── index.js            # Express server & Task API routes
│   └── package.json        # Backend dependencies (MySQL, Cloudinary)
└── frontend/
    ├── src/
    │   ├── components/     # UI components like Navbar
    │   ├── pages/          # Task dashboard and Feedback views
    │   └── App.jsx         # Application logic and routing
    └── index.html          # Main entry point with Tailwind CSS
```

---

## 🚀 Key Technical Highlights

* **Reliable Data Management:** I used **MySQL** with connection pooling to make sure the task list is always accurate and updates instantly without slowing down.
* **Cloud Integration:** Even for a task manager, I integrated **Cloudinary** so that any images or icons used within the app are hosted in the cloud, keeping the app fast and lightweight.
* **Modern UI Logic:** The app uses **React Router** to switch between your tasks and the feedback page without refreshing the browser, creating a smooth "App-like" feel.
* **Interactive Design:** I used **Framer Motion** to add subtle animations when tasks are added or completed, making the user experience more engaging.
