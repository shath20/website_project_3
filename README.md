# Liller Photo Website

Static portfolio website for Liller Photography, built with Showit.

## Running Locally

### Option 1: Double-Click Launcher (Windows)
Double-click `start_website.bat`.
It automatically launches a local Python web server on port 8000 and opens `http://localhost:8000` in your default browser.

### Option 2: Python Command Line
```powershell
python -m http.server 8000
```
Then navigate to [http://localhost:8000](http://localhost:8000).

### Option 3: Node.js (npx)
```powershell
npx serve .
```

---

## Deploying to GitHub Pages
To enable GitHub Pages:
1. Go to **Settings** > **Pages** in this GitHub repository.
2. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`.
4. Click **Save**.
