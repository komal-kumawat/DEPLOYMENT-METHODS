
🟦 1. Render (Best Full-stack Hosting)
🧠 Backend (Express.js)
Go to https://render.com

Login with GitHub → Click “New +” > Web Service

Choose your backend GitHub repo

Fill settings:

Name: your-backend-name

Environment: Node

Build Command: npm install

Start Command: node index.js (or your entry file)

Add Environment Variables:

Click “Add Environment Variable”

MONGO_URL → your MongoDB URI

Click Create Web Service

🟢 Your backend will be deployed. Copy the backend Render URL.

🎨 Frontend (React/Vite)
Back on Render dashboard → Click “New +” > Static Site

Choose your frontend GitHub repo

Fill:

Build Command: npm run build

Publish Directory: dist (Vite) or build (CRA)

Add environment variables if needed (e.g., API base URL):

VITE_BACKEND_URL → URL from your backend

Click Create Static Site

✅ Done! Your full stack is now live.

🟩
