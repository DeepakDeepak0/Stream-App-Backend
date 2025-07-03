# 📺 Stream-App - Video Streaming Application

Welcome to **Stream-App**, a full-stack video streaming platform built with **Spring Boot**, **React.js**, and **MySQL**. The application allows users to upload, stream, and manage videos with a seamless and modern UI/UX experience.

---

## ✨ Features

- 🎥 Video Upload & Streaming (MP4 support)
- 📁 Video Listing with Pagination & Search
- 📂 Categorized Video Management
- 📱 Fully Responsive Frontend (React + TailwindCSS)
- 📊 View Counts, Likes, and Comments (optional)
- 🚀 RESTful APIs for Frontend Integration

---

## 🛠️ Tech Stack

| Layer        | Technology                     |
|--------------|--------------------------------|
| Frontend     | React.js, Tailwind CSS         |
| Backend      | Spring Boot   |
| Database     | MySQL                          |
| Storage      | File System / Amazon S3 (optional) |
| Build Tools  | Maven                          |
| Version Ctrl | Git, GitHub                    |

---

## 📂 Project Structure


stream-App-Backend/
├── src/
│ ├── main/
│ │ ├── java/com/streamapp/...
│ │ └── resources/
│ └── test/
├── pom.xml
└── application.properties

stream-App-Frontend/
├── public/
├── src/
│ ├── components/
│ ├── pages/
│ ├── App.js
│ └── index.js
└── package.json

## ⚙️ Getting Started

### 🔧 Backend (Spring Boot)

```bash
# Navigate to backend folder
cd stream-App-Backend

# Configure database in application.properties
# Run the app
mvn spring-boot:run

🌐 Frontend (React)
bash
Copy
Edit
# Navigate to frontend folder
cd stream-App-Frontend

# Install dependencies
npm install

# Run development server
npm start

🙋‍♂️ Author
Deepak Maurya
