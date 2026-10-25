# ⚡ Stunn

## 🌐 Live Demo & Deployment

- **Frontend (Netlify):** [](stunnai.netlify.app)
- **Backend API (Render):** `https://stunn-tshm.onrender.com`
- **Backend Source Code:** [stunn-backend](https://github.com/VyomPROmax/stunn-backend)

## 🏗️ Architecture

Stunn uses a separately deployed frontend and backend.

- **Frontend:** Hosted on Netlify
- **Backend:** Hosted on Render
- **Source Control:** GitHub
- **Communication:** Frontend connects to the backend through API requests

## 🚀 Deployment

### Frontend
The frontend is deployed on Netlify.

### Backend
The backend source code is maintained on GitHub and deployed through Render.

Changes pushed to the connected repository can trigger a new deployment, depending on the Render configuration.

## 🔒 Security

- Keep API keys and secrets out of public repositories.
- Store sensitive environment variables in the hosting platform.
- Configure backend CORS to allow the intended frontend domain.
