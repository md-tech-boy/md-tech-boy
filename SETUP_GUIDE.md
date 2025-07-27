# 🚀 MD TECH HACKER - Local Setup Guide

## ⚠️ Important: Don't Open HTML Files Directly!

The error you're seeing happens when you try to open HTML files directly in the browser (file:// protocol). This causes CORS errors and breaks functionality.

## ✅ Correct Way to Run Locally

### Method 1: Python HTTP Server (Recommended)
```bash
# 1. Extract the ZIP file to any folder
# 2. Open terminal/command prompt in that folder
# 3. Run this command:
python3 -m http.server 8000

# 4. Open browser and go to:
http://localhost:8000
```

### Method 2: Using Node.js
```bash
# Install http-server globally
npm install -g http-server

# Navigate to extracted folder and run:
http-server -p 8000

# Open browser and go to:
http://localhost:8000
```

### Method 3: Using PHP (if installed)
```bash
# Navigate to extracted folder and run:
php -S localhost:8000

# Open browser and go to:
http://localhost:8000
```

## 🔧 With Flask Backend (Optional)
If you want dynamic features:

```bash
# Install Flask
pip install Flask flask-cors

# Run backend (in one terminal)
python3 app.py

# Run frontend (in another terminal)
python3 -m http.server 8000
```

## 📁 What's Included
- ✅ Homepage with modern design
- ✅ Methods page with tutorials
- ✅ Bins page with BIN collection
- ✅ Accounts system
- ✅ Support page
- ✅ Admin panel
- ✅ Dark/Light theme toggle
- ✅ Responsive design
- ✅ All JavaScript functionality

## 🎯 Quick Fix for Your Current Issue
1. Don't double-click HTML files
2. Use a local server (Python method above)
3. Access via http://localhost:8000

## 📞 Need Help?
Contact: @MD_TECH_HACKER on Telegram

---
**Remember: Always use a local server, never open HTML files directly!**
