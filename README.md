# The Movement

A recruitment and pathway portal for systematic change initiatives.

## Features

- **Strategic Pathway**: Three-phase operational model (Assembly, Coordination, Execution)
- **Recruitment Form**: Collect applicant information with skill categorization
- **Dark Theme**: GitHub-inspired dark mode interface
- **Responsive Design**: Works across all device sizes
- **Form Integration**: Connected to Formspree for email notifications

## Project Structure

```
the-movement/
├── index.html      # Main recruitment portal page
└── README.md       # This file
```

## Setup

1. Clone the repository:
```bash
git clone https://github.com/ridayvishwas9-bit/the-movement.git
cd the-movement
```

2. Open `index.html` in your browser or deploy to a web server

## Form Configuration

The recruitment form is configured to use **Formspree** for form submissions. Update the form action URL in `index.html` if needed:

```html
<form id="recruitForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## Customization

### Colors
Modify the CSS variables in the `<style>` section:
- `--bg-color`: Background color
- `--text-color`: Text color
- `--accent-color`: Accent/highlight color
- `--section-bg`: Section background color
- `--border-color`: Border color

### Content
Update the following sections to customize:
- Header title and subtitle
- Pathway phases (Phase 1, 2, 3)
- Form fields and labels

## Deployment

### GitHub Pages
1. Go to repository Settings → Pages
2. Set source to `main` branch
3. Your site will be live at `https://ridayvishwas9-bit.github.io/the-movement`

### Other Hosting
Deploy `index.html` to any static hosting service (Vercel, Netlify, etc.)

## License

MIT License - feel free to use and modify

---

**Last Updated**: 2026-07-22
