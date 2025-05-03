## 🌐 Deploying on Netlify (Frontend & Backend)

### 🎨 Frontend (React/Vite)

1. Go to [Netlify](https://netlify.com)
2. Log in with GitHub
3. Click **Add New Site > Import from Git**
4. Choose frontend repo
5. Fill settings:
   - **Build Command**: `npm run build`
   - **Publish Directory**: `dist` (Vite) or `build` (CRA)
6. Add Environment Variable:
   - Key: `VITE_BACKEND_URL`
   - Value: *Your backend URL*

---

### 🧠 Backend Options

- **Option 1**: Host backend separately on Render/Railway/Cyclic
- **Option 2**: Use [Netlify Functions](https://docs.netlify.com/functions/overview/) for small APIs

✅ App is deployed on Netlify!
