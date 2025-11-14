# Personal Academic Website

A minimalistic, professional personal website for an undergraduate researcher. Clean design with white background, dark text, and Inter font.

## Project Structure

```
.
├── index.html              # Landing page with profile, about, and news
├── papers.html             # Publications and projects page
├── assets/
│   ├── cv.pdf             # CV document (opens in new tab)
│   └── images/
│       └── headshot.jpg   # Profile photo
├── css/
│   └── style.css          # Main stylesheet (minimalist design)
├── js/
│   └── main.js            # JavaScript for interactions
└── README.md              # This file
```

## Design Features

- **Minimalist Design**: Clean white background with dark text
- **Typography**: Inter font family (Google Fonts)
- **Responsive Layout**: Works on desktop, tablet, and mobile
- **Smooth Transitions**: Hover effects and fade-in animations
- **Icon Links**: Font Awesome icons for social media

## Pages

### Home (index.html)
- Centered headshot image
- Name and title
- Contact icons (Email, GitHub, LinkedIn, Google Scholar)
- About Me section
- Recent Updates (news) section

### Papers + Code (papers.html)
- **Papers Section**: Academic publications with PDF/code/arXiv links
- **Projects Section**: GitHub projects and demos

### CV
- Direct link to CV PDF that opens in a new tab

## Navigation

Top navigation bar with:
- Home
- Papers + Code
- CV (opens PDF in new tab)

## Quick Start

### Run Locally

**Option 1: Python**
```bash
python3 -m http.server 8000
```

**Option 2: Node.js**
```bash
npx http-server -p 8000
```

Then open `http://localhost:8001` in your browser.

### Deploy to GitHub Pages

1. Create a repository named `username.github.io`
2. Push all files to the repository
3. Enable GitHub Pages in repository settings
4. Your site will be live at `https://username.github.io`

## Customization

### Update Profile Information

**In `index.html`:**
- Replace headshot image: `assets/images/headshot.jpg`
- Edit name, title, and bio text
- Update contact links (email, GitHub, LinkedIn, Google Scholar)
- Modify news items

**In `papers.html`:**
- Add/edit papers in the Papers section
- Add/edit projects in the Projects section
- Update links to PDFs, code repositories, and demos

**CV:**
- Replace `assets/cv.pdf` with your CV

### Change Colors

Edit `css/style.css`:
- Primary blue: `#2563eb`
- Text color: `#1a1a1a`
- Gray text: `#4b5563`, `#6b7280`
- Borders: `#e5e7eb`
- Background: `#ffffff`

### Change Font

In HTML files, update the Google Fonts link and CSS font-family:
```css
font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', system-ui, sans-serif;
```

## Browser Compatibility

Compatible with all modern browsers:
- Chrome, Edge, Safari, Firefox (latest versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## References

Design inspired by:
- [tianlong-chen.github.io](https://tianlong-chen.github.io)
- [peterbhase.github.io](https://peterbhase.github.io)
- [esteng.github.io](https://esteng.github.io)

## License

Free to use for personal academic websites.

---

Built with HTML, CSS, and vanilla JavaScript. No frameworks required.
