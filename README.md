# 🎮 Secret Arcade Web Viewer

A retro arcade-themed web viewer that can be embedded in Google Sites. Enter any website URL and browse it within the application.

## Features

✨ **Dark Arcade Theme** - Stylish UI with blue/purple color scheme  
📱 **Responsive Design** - Works on desktop, tablet, and mobile  
🔗 **URL Validation** - Automatic HTTPS protocol detection  
⌨️ **Keyboard Support** - Press Enter to load websites  
🎯 **Real-time Status** - Loading indicators and error messages  

## How to Use

### Standalone
1. Download `index.html`
2. Open it in any web browser
3. Enter a website URL and click GO

### Embed in Google Sites

Follow these steps to add the Secret Arcade Web Viewer to your Google Site:

#### Step 1: Host the File
You have two options:

**Option A: Use GitHub Pages (Free & Recommended)**
- This repo is already set up for GitHub Pages
- The file is available at: `https://raw.githubusercontent.com/ezrabackus-max/secret-arcade-web-viewer/main/index.html`

**Option B: Host Elsewhere**
- Upload `index.html` to any web hosting service (Replit, Netlify, etc.)
- Get the public URL to the file

#### Step 2: Add to Google Sites
1. Open your Google Site
2. Click **Insert** → **Embed code**
3. Copy and paste this code:

```html
<iframe 
  src="https://raw.githubusercontent.com/ezrabackus-max/secret-arcade-web-viewer/main/index.html" 
  style="width: 100%; height: 800px; border: none; border-radius: 10px;"
  title="Secret Arcade Web Viewer"
  allow="fullscreen">
</iframe>
```

4. Click **Insert**
5. Adjust the width/height in the embed code as needed (currently 800px height)

#### Step 3: Optional Customization
- Change `height: 800px` to make it taller or shorter
- Change `width: 100%` to a fixed pixel value if desired
- The embedded viewer will work exactly like the standalone version

## Limitations

⚠️ Some websites block embedding due to CORS/X-Frame-Options headers  
⚠️ Works best with sites that allow iframes  

## Browser Support

- Chrome/Edge ✅
- Firefox ✅
- Safari ✅
- Mobile Browsers ✅

## Files

- `index.html` - Complete web viewer (all-in-one file)
- `README.md` - This documentation

## License

Free to use and modify for personal or commercial projects.

---

**Tips for Best Results:**
- Test embedding with public websites first (Wikipedia, BBC, etc.)
- If a site doesn't load, it likely has embedding restrictions
- Use the CLEAR button to reset and try another URL
- The viewer is fully self-contained—no additional dependencies needed
