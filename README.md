# NovaSphere Analytics — Company Portfolio Website

NovaSphere Analytics is a data and AI consulting company specialising in predictive analytics, cloud-based data solutions, business intelligence, and machine learning. This repository contains the company's portfolio website, built to showcase the team, projects, and services offered by NovaSphere Analytics.

---

## Live Site

> Add your live URL here once deployed (e.g. `https://novasphere-analytics.com`)

---

## About the Project

This is a static company portfolio website designed to present NovaSphere Analytics to potential clients and partners. It highlights the company's core capabilities, featured projects, and the team behind the work.

### Pages and Sections

- **Home** — Hero banner with company introduction and mission statement
- **About** — Overview of NovaSphere Analytics, its focus areas, and value proposition
- **Projects** — Showcase of four key data science projects:
  - Predictive Analytics for Healthcare
  - Cloud-Based Data Warehouse
  - Business Intelligence Dashboard
  - Machine Learning for Customer Segmentation
- **Team** — Profiles of team members with roles and bios
- **Contact** — Contact information and enquiry section

---

## Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Page structure and content |
| CSS3 | Styling, layout, and responsive design |

No frameworks, libraries, or build tools are required. The site runs entirely in the browser with no dependencies.

---

## Project Structure

```
novasphere-analytics/
├── resources/
│   ├── css/            # Stylesheets
│   └── images/         # Project and team images
├── .gitignore          # Git ignore rules
├── favicon.ico         # Site favicon
├── index.html          # Main HTML file
└── README.md           # Project documentation
```

---

## Getting Started

No installation or build process is needed. Simply clone the repository and open the HTML file in your browser.

```bash
# Clone the repository
git clone https://github.com/your-username/novasphere-analytics.git

# Navigate into the project folder
cd novasphere-analytics

# Open in your browser
open index.html
```

---

## Logo

The NovaSphere Analytics logo is an inline SVG embedded directly in the navbar. It features an orbital sphere icon representing data connectivity, with "Nova" in dark navy and "Sphere" in brand blue. To resize the logo without affecting the navbar height, control its size via CSS:

```css
#logo svg {
  width: 180px;
  height: auto;
}
```

---

## Customisation

To update site content, edit `index.html` directly. Key areas to update:

- **Company description** — located in the hero/about section
- **Project cards** — update titles, images, and descriptions in the Projects section
- **Team cards** — update names, roles, photos, and bios in the Team section
- **Contact details** — update email, phone, or social links in the Contact section

---

## Deployment

Since the site is built with plain HTML and CSS, it can be deployed to any static hosting platform:

- [GitHub Pages](https://pages.github.com)
- [Netlify](https://netlify.com)
- [Vercel](https://vercel.com)

---

## License

This project is the property of NovaSphere Analytics. All rights reserved.
