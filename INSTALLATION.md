# 📦 Installation & Setup

## Local Development

### Option 1: Python (Easiest)
```bash
python3 -m http.server 8000
```
Then visit: `http://localhost:8000`

### Option 2: Node.js
```bash
npm install -g http-server
http-server
```
Then visit: `http://localhost:8080`

### Option 3: VS Code Live Server
1. Install "Live Server" extension
2. Right-click `index.html`
3. "Open with Live Server"

## File Descriptions

### `index.html` (8.7 KB)
- Main website home page
- Categories section
- Featured products
- Shopping cart button
- Firebase integration

### `admin.html` (14 KB)
- Complete admin dashboard
- Add/Edit/Delete products
- Manage categories
- View orders
- Site settings
- Firebase integration

### `netlify.toml`
- Netlify configuration
- Handles SPA routing

### `package.json`
- Project metadata
- Scripts for local development

## Requirements

- Text editor (VS Code, Sublime, etc.)
- Git (for GitHub)
- Web browser

**No installation needed!** Files are ready to use.

## Next Steps

1. **Test locally** (use Python/Node server above)
2. **Create GitHub repo** (see DEPLOY_GUIDE.md)
3. **Deploy to Netlify** (automatic from GitHub)
4. **Add products** via Admin Panel
5. **Share your store!** 🎉

---

**All set?** Go to DEPLOY_GUIDE.md!
