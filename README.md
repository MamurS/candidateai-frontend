# CandidateAI Frontend

A modern single-page web application for CandidateAI job matching platform, ready for production deployment.

## ✨ Features

- 🔐 **Secure Authentication** - User registration, login, and OTP verification
- 📄 **CV Analysis** - AI-powered CV upload and analysis with skill extraction
- ⚙️ **Work Preferences** - Comprehensive job preference management
- 🔍 **Smart Job Search** - AI-powered job matching with detailed results
- 📱 **Responsive Design** - Modern UI with mobile-first approach
- 🎨 **Premium Design** - ShadCN-inspired design system with glass morphism

## 🚀 Quick Deploy on Render

### Option 1: Static Site (Recommended)
1. Fork or clone this repository to GitHub
2. Go to [render.com](https://render.com) and create a new **Static Site**
3. Connect your GitHub repository
4. Configure:
   - **Build Command**: (leave empty)
   - **Publish Directory**: `.`
5. Click **Deploy**
6. Your app will be live at `https://your-app-name.onrender.com`

### Option 2: Web Service (Advanced)
1. Push this repository to GitHub
2. Create a new **Web Service** on Render
3. Configure:
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `python serve.py`
4. Deploy and enjoy automatic HTTPS and global CDN

## 🛠️ Local Development

```bash
# Simple HTTP server
python3 -m http.server 8000

# Or use the custom server
python serve.py
```

Then open http://localhost:8000

## 🔗 Backend Integration

This frontend seamlessly integrates with the CandidateAI backend:
- **API Base**: `https://candidate-backend-6l1l.onrender.com`
- **Authentication**: JWT tokens with automatic refresh
- **File Upload**: Direct CV upload with progress tracking
- **Real-time Search**: Instant job matching results

## 🏗️ Architecture

- **Single HTML File** - Complete application in one file for easy deployment
- **No Build Process** - Pure HTML/CSS/JS, no compilation needed
- **Production Ready** - Optimized for performance and SEO
- **CORS Compliant** - Works seamlessly when deployed to any hosting service

## 🎨 Design System

- **Colors**: HSL-based color system with CSS custom properties
- **Typography**: Inter font family with perfect spacing
- **Components**: Card-based layout with consistent spacing
- **Animations**: Smooth transitions and micro-interactions
- **Responsive**: Mobile-first design with fluid grids

## 📦 Technologies

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Modern CSS with custom properties, gradients, and backdrop-filter
- **API**: RESTful integration with comprehensive error handling
- **Deployment**: Static hosting compatible (Render, Netlify, Vercel)

## 🌟 Production Features

- ✅ No CORS issues when deployed
- ✅ Automatic HTTPS encryption
- ✅ Global CDN for fast loading
- ✅ Professional domain (your-app.onrender.com)
- ✅ Zero configuration deployment
- ✅ Automatic deployments from GitHub

---

Ready to deploy? Just push to GitHub and connect to Render! 🚀 