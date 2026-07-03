# Ziqian Chen's Personal Homepage

A personal academic homepage adapted from the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme.

## Quick Start

1. **Add your profile photo**: Place a square photo named `profile.jpg` in `assets/profile.jpg`

2. **Preview locally**:
   ```bash
   cd homepage
   python3 -m http.server 8000
   ```
   Then open http://localhost:8000

3. **Deploy to GitHub Pages**:
   - Create a repo named `<username>.github.io`
   - Push the contents of the `homepage/` folder to the repo
   - Your site will be live at `https://<username>.github.io`

## Customization

- Edit `index.html` to update content
- Edit `assets/main.css` for styling changes
- Replace `assets/profile.jpg` with your own photo (square, at least 250x250px)

## File Structure

```
homepage/
├── index.html          # Main page
├── assets/
│   ├── main.css        # Theme styles
│   ├── main.min.js     # Navigation & interactions
│   ├── academicons.css # Academic icons
│   └── profile.jpg     # Your profile photo (add this)
└── README.md
```

## Credits

- Theme: [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) by Michael Rose
- Reference design: Xiang Li's homepage
