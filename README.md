
# TechBlog – Personal Technology Blog

**TechBlog** is a responsive, modern, and clean personal blog template built for technology writers, digital strategists, and creators who want a stylish and professional web presence. It includes sections for about, skills, blog posts, and contact, with support for interactive UI elements and mobile-friendly layouts.

---

## Project Overview

TechBlog is a static website built with HTML, CSS, and JavaScript. It offers a sidebar layout with featured profile info, smooth scrolling effects, and content sections that can be easily customized and extended. Ideal for personal branding, content publishing, and showcasing professional skills.

---

## Features

### UI & Layout
- **Responsive Design**: Mobile, tablet, and desktop support.
- **Modern Sidebar Profile**: Fixed profile info and social links.
- **Grid Blog Layout**: Clean preview of all articles.
- **Single Post Page**: Full article view with images and code blocks.

### Interactive Elements
- Mobile navigation menu
- Scroll-triggered animations
- Animated skill bars
- Back to top button
- Social media icons

### Content Sections
- About page with bio & image
- Visual skills section
- Blog with individual posts
- Contact form and social links

---

## Technologies Used

### Frontend
- HTML5
- CSS3 (with CSS Variables)
- JavaScript (ES6)
- Font Awesome (icons)
- Google Fonts (Open Sans)

### JS Dependencies
- jQuery 3.4.1
- Waypoints.js
- Easing animation library
- jqBootstrapValidation (form validation)

---

## File Structure

```
charles-blog/
├── index.html              # Homepage
├── about.html              # About/Bio page
├── blog.html               # Blog overview
├── single.html             # Blog post template
├── contact.html            # Contact form
├── css/
│   └── style.css           # Main CSS styles
├── js/
│   ├── main.js             # Custom JS
│   ├── easing.min.js       # Easing animations
│   └── waypoints.min.js    # Scroll detection
├── img/                    # Images folder
│   ├── profile.jpg
│   ├── about.jpg
│   ├── header-bg.jpg
│   └── favicon.ico         # Favicon (optional)
├── mail/
│   ├── contact.js
│   └── jqBootstrapValidation.min.js
└── README.md               # This file
```

---

## Installation & Usage

### Local Use
No server needed. Just download and open `index.html` in your browser.

### Development
```bash
git clone https://github.com/charles-mori/techblog
cd techblog
```

---

## ✏️ Customization

### Images & Text
- Replace `img/profile.jpg` and `img/about.jpg` with your own.
- Update content in HTML files: bio, blog titles, contact details, etc.

### Color Theme
Edit variables in `css/style.css`:
```css
:root {
  --primary-color: #3498db;
  --secondary-color: #2c3e50;
  --light-color: #ecf0f1;
  --text-color: #333;
}
```

### Adding New Blog Posts
1. Duplicate `single.html` and rename (e.g. `post-title.html`).
2. Replace content with your post.
3. Link the new post in `blog.html`.

---

## Deployment

### GitHub Pages
1. Push your project to a public GitHub repo.
2. Go to **Settings > Pages**.
3. Choose main branch, root folder, and hit "Save".

### Netlify
- Drag & drop your folder to [Netlify](https://netlify.com) or connect your repo.

### Vercel
- Import from GitHub to [Vercel](https://vercel.com) and deploy instantly.

---

## License

This project is licensed under the **MIT License**.  
You're free to use, modify, and share with credit.  
See the `LICENSE` file for full terms.

---

## Credits
- Font Awesome for icons
- Google Fonts for typography
- jQuery and associated plugins for interactivity

---

## Contact

Questions, feedback, or contributions?

- Email: [charles@techblog.com]
- Website: [https://techblog.com]
