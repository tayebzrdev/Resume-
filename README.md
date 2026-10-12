# Tayebzr.dev — Personal Portfolio

A modern, bilingual personal portfolio website created to showcase my web design skills, frontend development projects, and professional background.

The website features a dark interface, gradient accents, responsive layouts, animated elements, and Persian/English language support.

## Features

- **Bilingual Interface:** Persian (RTL) and English (LTR) language support.
- **Responsive Design:** Layouts adapted for desktop, tablet, and mobile screens.
- **Project Showcase:** Dedicated cards for presenting web development projects.
- **Video Previews:** Modal windows for watching short project demonstrations.
- **Live Project Links:** Direct links to deployed projects when available.
- **Demo Project Management Panel:** Displays project data stored in browser localStorage.
- **Interactive UI:** Animated elements, scroll reveals, and a mobile navigation menu.
- **Contact Form:** Opens the user's default email application with a pre-filled message.
- **SEO & Social Metadata:** Includes page descriptions and Open Graph metadata.
- **Custom Branding:** A dark visual identity with blue, purple, and pink gradients.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Google Fonts
- Browser localStorage
- Intersection Observer API

## Project Structure

```text
tayebzr-personal-portfolio/
├── index.html
├── images/
│   ├── favicon/
│   ├── haddad-bearing.webp
│   ├── one-percent.webp
│   └── kahkeshan.webp
├── videos/
│   ├── haddad-bearing-clip.mp4
│   ├── demo-clip.mp4
│   └── kahkeshan-clip.mp4
├── admin/
│   └── index.html
└── README.md
```

*Note: The structure above is illustrative. Adjust it to match the actual files and folders in the repository.*

## Project Management Panel

The demo management panel supports displaying project information saved in the browser's localStorage.

Project data is read from the `adm_projects` key. Visible projects can be rendered dynamically on the portfolio page.

This is a frontend-only demonstration and does not provide server-side authentication, a database, or secure multi-user administration.

## Contact Form

The contact form uses a `mailto:` link to open the visitor's default email application with the message details pre-filled. It does not send messages through a backend service.

## Getting Started

1. Clone or download this repository.
2. Open `index.html` in a browser, or run the project using a local development server.
3. Make sure the referenced image and video assets are present in their expected directories.
4. Update project details and contact links to match your own information.

## Author

**Tayebeh Zare**  
Web Designer & Frontend Developer

- Portfolio: `https://YOUR-LIVE-PORTFOLIO-URL`
- GitHub: `https://github.com/tayebehzare`

## License

This project is available for viewing and learning purposes. Add a license file if you intend to grant specific reuse or redistribution permissions.
