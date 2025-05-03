## 🟦 Deploying Full Stack App on Render

### 🧠 Backend (Express.js)

1. Go to [Render](https://render.com)
2. Log in with your GitHub account
3. Click **“New +” > Web Service**
4. Choose your backend GitHub repository
5. Configure the service:
   - **Name**: `your-backend-name`
   - **Environment**: `Node`
   - **Build Command**: `npm install`
   - **Start Command**: `node index.js` *(or your main file)*
6. Add Environment Variables:
   - Click **“Add Environment Variable”**
   - Key: `MONGO_URL`
   - Value: *your MongoDB connection string*
7. Click **“Create Web Service”**

> 🟢 Your backend will be deployed. Copy the backend Render URL for the frontend.

---

### 🎨 Frontend (React/Vite)

1. Go back to the Render dashboard
2. Click **“New +” > Static Site**
3. Choose your frontend GitHub repository
4. Configure the service:
   - **Build Command**: `npm run build`
   - **Publish Directory**: `dist` (for Vite) or `build` (for Create React App)
5. Add environment variables if needed:
   - Key: `VITE_BACKEND_URL`
   - Value: *your backend Render URL*
6. Click **“Create Static Site”**

> ✅ Your full stack application is now deployed and live!
