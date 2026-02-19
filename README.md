# Competitive Intelligence Tracker - Frontend

This is the static frontend for the Intelligence Tracker. It acts as a dashboard consumed by the backend API.

## 🚀 Deployment (Vercel)

1. **Deploy to Vercel**:
   - Drag and drop this folder (or connect GitHub).
   - It is a plain **Static HTML** site. No build command needed.

2. **Connect to Backend**:
   - In your backend deployment (Railway), find your **Public URL** (e.g., `https://your-app.up.railway.app`).
   - Open `config.js` in this repo and update the `API_BASE_URL`:
   
   ```javascript
   const API_BASE_URL = "https://your-app.up.railway.app";
   ```

   *(Note: For a real production app, we would inject this at build time, but for this simple static site, editing the file is easiest.)*

## 🛠️ Local Development

1. Open `index.html` in your browser.
2. Ensure the Backend is running on `http://localhost:8000`.
