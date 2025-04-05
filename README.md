# 🚀 HackerNews Server

A lightning-fast backend for social news—powered by **Node.js**, **Hono**, **Prisma**, and **Supabase**.

---

## ✨ Features

- 🔐 JWT Authentication  
- 🛠️ CRUD for Users, Posts, Likes, Comments  
- 🔒 SHA256 Password Hashing  
- 🧩 Role-Based Middleware  
- 📄 Pagination Support  
- 🧱 Modular Folder Structure  

---

## 🔧 Tech Stack

- **Node.js** + **TypeScript**  
- **Hono** (Ultra-fast web framework)  
- **Prisma ORM**  
- **Supabase** (Auth + DB)

---

## ⚙️ Setup

```bash
Create a .env file:

env
Copy
Edit
PORT=3000
JWT_SECRET=your_secret
SUPABASE_URL=your_url
SUPABASE_KEY=your_key
🚀 Run
bash
Copy
Edit
npm run dev      # Development
npm start        # Production
Server runs at: http://localhost:3000

📌 API Highlights
🔐 Auth
POST /auth/sign-up – Register

POST /auth/log-in – Login

👤 Users
GET /users/me – My Profile

GET /users – All Users (paginated)

📝 Posts
GET /posts – All Posts (latest first)

POST /posts – Create

DELETE /posts/:id – Delete

❤️ Likes
GET /likes/on/:postId – Post Likes

POST /likes/on/:postId – Like

DELETE /likes/on/:postId – Unlike

💬 Comments
GET /comments/on/:postId

POST /comments/on/:postId

PATCH /comments/:commentId

DELETE /comments/:commentId

🗂️ Project Structure
css
Copy
Edit
src/
├── controllers/
├── middleware/
├── models/
├── routes/
├── services/
├── app.ts
└── server.ts
🤝 Contributing
🍴 Fork the repo

🔧 Create a branch

💡 Commit your changes

🚀 Push and PR

📄 License
Licensed under the MIT License

💡 "Built for speed, security & simplicity—powering the next-gen discussions!"

vbnet
Copy
Edit

Let me know if you want me to customize it further (like adding badges, screenshots, or deploy instructions).
git clone https://github.com/Nafeessidd1/hackernews-server.git
cd hackernews-server
npm install


