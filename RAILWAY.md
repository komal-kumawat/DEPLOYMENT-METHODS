## 🚄 Deploying Full Stack App on Railway

### 🧠 Backend (Node/Express)

1. Go to [Railway](https://railway.app)
2. Click **Start New Project > Deploy from GitHub**
3. Choose backend repo
4. Set:
   - **Build Command**: `npm install`
   - **Start Command**: `node index.js`
5. Add Environment Variable:
   - Key: `MONGO_URL`
   - Value: *MongoDB URI*
6. Click **Deploy**

🔗 Copy the backend public URL

---

### 🎨 Frontend (React/Vite)

Use **Vercel**, **Netlify**, or **Render** for frontend

Set:
- `VITE_BACKEND_URL = [Railway backend URL]`

✅ You're done!
