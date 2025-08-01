# 🚀 Deployment Instructions for KoriRemover

## Quick Deploy Options

### 1. Render (Recommended - Free)

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/runeimport/KoriWeb)

**Manual Steps:**
1. Go to [render.com](https://render.com)
2. Connect your GitHub account
3. Create a new "Web Service"
4. Select repository: `runeimport/KoriWeb`
5. Configure:
   - **Root Directory**: `KoriRemoverApp`
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `gunicorn --bind 0.0.0.0:$PORT app_basic:app`
   - **Environment**: Python 3

### 2. Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/runeimport/KoriWeb)

### 3. Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/runeimport/KoriWeb)

## Features

✅ **Real AI Background Removal** (using rembg library)
✅ **Multiple Image Formats** (PNG, JPG, JPEG, GIF, BMP, WEBP)
✅ **Drag & Drop Interface**
✅ **Batch Processing**
✅ **Download Processed Images**
✅ **Mobile Responsive**

## Live Demo

- **Full App**: [Deploy your own](https://render.com/deploy?repo=https://github.com/runeimport/KoriWeb)
- **Static Demo**: https://runeimport.github.io/KoriWeb/koriremover/docs/

## Local Development

```bash
cd KoriRemoverApp
pip install -r requirements.txt
python app_basic.py
```

Visit: http://localhost:5000
