## 🔁 Deploying Backend on Cyclic.sh

### 🧠 Backend (Node/Express)

1. Go to [Cyclic](https://www.cyclic.sh)
2. Log in with GitHub
3. Click **“Deploy”**
4. Choose your backend repo
5. It auto-installs and deploys
6. Set Environment Variables:
   - Key: `MONGO_URL`
   - Value: *MongoDB URI*
7. Click **View App**

🔗 Copy backend URL for frontend use

---

### 🎨 Frontend

Use Vercel/Netlify/Render for frontend

Set:
- `VITE_BACKEND_URL = [Cyclic backend URL]`

✅ Project is live!
