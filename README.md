# 🚀 Full Stack AI SaaS App

Build and deploy a modern **AI-powered SaaS application** from scratch using the **PERN Stack (PostgreSQL, Express.js, React.js, Node.js)**.  

The website features a clean and responsive frontend built with React and Tailwind CSS, secure authentication powered by Clerk, and AI tools integrated through APIs like OpenAI and ClipDrop. It uses PostgreSQL for database-backed workflows, a robust REST API with Express and Node.js, and is fully deployed on the cloud for a production-ready experience.  



---

## ✨ Features

- 🖼 **AI-Powered Features** — integrate image generation, text prompts, etc.  
- 📦 **Full PERN Stack** setup:  
  - **PostgreSQL** – relational database  
  - **Express.js** – server & API handling  
  - **React.js** – modern frontend with hooks  
  - **Node.js** – backend runtime  
- 📡 **REST API** endpoints for secure data exchange  
- 🎨 **Modern UI/UX** with Tailwind CSS & clean component design  
- 🌐 **Deployment** to production (Vercel/Render/Railway + database hosting)  
- 🔥 **Persistent State & Data Management**  
- 🛠 **Scalable Project Structure** for real-world SaaS apps

---

## 🛠️ Tech Stack

**Frontend**
- React.js  
- Tailwind CSS  
- Axios (API calls)  

**Backend**
- Node.js  
- Express.js  
- PostgreSQL (with Neon)  

**Other Tools**
- Clerk (Authentication)  
- Cloudinary (Media uploads)  
- OpenAI API / AI integrations  
- Vercel, Render (Deployment options)  

---

## 📂 Project Structure

```bash
├── client/                # React frontend
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Page-level components
│   │   ├── utils/         # Helpers & configs
│   │   └── App.tsx
│   └── package.json

├── server/                # Express backend
│   ├── routes/            # API routes
│   ├── controllers/       # Logic for handling requests
│   ├── middlewares/       # Authentication & validation
│   ├── db/                # Database connection
│   └── server.js

├── .env                   # Environment variables
├── .gitignore
└── README.md
```

---

## ⚡ Getting Started

1️⃣ Clone the repo
```
git clone https://github.com/biru-ka2/AI-SaaS-App.git
cd ai-saas-pern

```

2️⃣ Install dependencies
```
# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install

```

3️⃣ Setup environment variables
Create a .env file in both client and server with the following:

```
# Server
DATABASE_URL=postgresql://USER:PASSWORD@localhost:5432/dbname
CLERK_API_KEY=your_clerk_api_key
CLOUDINARY_API_KEY=your_cloudinary_key
OPENAI_API_KEY=your_openai_key

# Client
VITE_CLERK_PUBLISHABLE_KEY=your_publishable_key

```

4️⃣ Run the development servers
```
# Start backend
cd server
npm run dev
# Start frontend
cd ../client
npm run dev
```
Now visit http://localhost:5173 🎉

---

## 🚀 Deployment

- Frontend → Vercel

- Backend → Render/ Railway

- Database → Supabase/ Neon/ Railway

Push your code to GitHub and connect your repo to these platforms for one-click deployment.

---

## 🧠 Learning Goals

**By the end of this project you’ll:**

- Understand full-stack PERN workflows
- Learn how to integrate AI APIs into real apps
- Gain practical experience with authentication & cloud deployments
- Build a portfolio-worthy SaaS product

---

## 📬 Contact

For feedback or inquiries, please reach out at harshkurware03@gmail.com. <br>
*This project is licensed under the MIT License.*

