## ⚫ Deploying on Vercel (Frontend & Serverless API)

### 🎨 Frontend (React/Vite)

1. Go to [Vercel](https://vercel.com)
2. Log in with GitHub
3. Click **New Project** > Select frontend repo
4. Set:
   - **Framework**: React or Vite
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist` or `build`
5. Set Environment Variable:
   - Key: `VITE_BACKEND_URL`
   - Value: *Your backend URL (Render/Railway/etc.)*
6. Click **Deploy**

---

### 🧠 Backend Options

- **Option 1**: Deploy backend separately on Render or Railway
- **Option 2**: Use Vercel API routes (`/api/hello.js`) for small serverless endpoints

✅ You're live!
