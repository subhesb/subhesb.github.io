# Subhesb Personal Academic Website

A professional academic portfolio website hosted on GitHub Pages.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Top Navigation Menu**: Easy access to all content categories:
  - Home
  - Journal Papers
  - Book Chapters
  - Books
  - Reports
  - Conference Papers & Presentations
  - Talks & Seminars
  - Tools & Resources
  - Reviews
  - Blogs

- **Sidebar**: Quick links to:
  - New Posts
  - Updates
  - Quick Links (GitHub, LinkedIn, Email, etc.)

- **Main Content Area**:
  - Recent works showcase
  - Recent debates/discussions
  - Individual pages for each content type

## Structure

```
subhesb.github.io/
├── index.html                 # Homepage
├── css/
│   └── style.css             # Main stylesheet
├── pages/
│   ├── journal-papers.html
│   ├── book-chapters.html
│   ├── books.html
│   ├── reports.html
│   ├── conference-papers.html
│   ├── talks.html
│   ├── tools.html
│   ├── reviews.html
│   └── blogs.html
└── README.md
```

## Setup Instructions

1. Your website is now live at: `https://subhesb.github.io`

2. **Customization**:
   - Edit the content in each HTML file to add your publications, talks, and information
   - Update links in the sidebar (GitHub, LinkedIn, email, etc.)
   - Modify colors in `css/style.css` if desired

3. **Adding New Content**:
   - Add blog posts to `pages/blogs.html`
   - Add papers to `pages/journal-papers.html`
   - Update the sidebar with new posts and updates in `index.html`

## Customization Guide

### Colors
The main color scheme uses:
- Primary: `#2c3e50` (dark blue-grey)
- Accent: `#3498db` (bright blue)
- Background: `#f5f5f5` (light grey)

To change colors, edit the CSS variables in `css/style.css`.

### Adding Social Links
Edit the Quick Links section in the sidebar to include your:
- GitHub profile
- LinkedIn profile
- Email address
- ORCID profile
- ResearchGate profile

### Blog Posts
Add new blog posts to `pages/blogs.html` by creating new `<article class="blog-post">` elements.

## Features to Consider Adding

- Search functionality
- Publication filters by year/topic
- Dark mode toggle
- Comments section
- RSS feed
- Citation export (BibTeX, APA, etc.)
- Analytics

## License

Feel free to customize and use this template for your personal academic website.
