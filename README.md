# Course Campus

**Learn. Grow. Succeed.**

Course Campus is a responsive, multi-page educational guidance website for students exploring open schooling, distance education, college degree programs, and career pathways. The site presents information about NIOS and IGNOU support, course options, career guidance, frequently asked questions, and ways to contact the Course Campus team.

## Live Website

[Visit Course Campus](https://coursecampus.netlify.app)

## Website Features

- Multi-page website with Home, About, Courses, Career Guidance, NIOS Support, FAQ, and Privacy Policy pages.
- Information about NIOS, IGNOU, distance education, and selected degree and teaching-related programs.
- Responsive navigation and mobile-friendly navigation elements.
- Course and career information to help visitors explore possible study paths.
- FAQ content to answer common questions about educational guidance and admissions assistance.
- WhatsApp and telephone links for enquiries.
- Enquiry form integration using Formspree.
- Reusable CSS styling, interactive JavaScript behaviour, and image assets.

## Pages

| File | Purpose |
|---|---|
| `index.html` | Homepage and overview of Course Campus services |
| `about.html` | About Course Campus and its mission |
| `courses.html` | Course and program information |
| `career.html` | Career guidance and study pathways |
| `nios.html` | NIOS and open-schooling information |
| `faq.html` | Frequently asked questions |
| `privacy.html` | Website privacy policy |

## Technology Stack

- **HTML5** — page structure and content
- **CSS3** — layout, styling, and responsive design
- **JavaScript** — navigation and interactive website behaviour
- **Google Fonts (Inter)** — typography
- **Font Awesome** — interface icons
- **Formspree** — enquiry form processing
- **Vercel configuration** — included in `vercel.json` for static-site deployment

## Project Structure

```text
Course-Campus-Website/
├── index.html
├── about.html
├── career.html
├── courses.html
├── faq.html
├── nios.html
├── privacy.html
├── vercel.json
├── css/
│   └── style.css
├── js/
│   └── main.js
└── public/
    ├── assets/
    │   ├── logo.png
    │   ├── ashu-sir.jpg
    │   └── class*.jpg
    ├── favicon.svg
    ├── opengraph.jpg
    └── robots.txt
```

## Run Locally

This is a static HTML, CSS, and JavaScript website. No Node.js build step is defined in the project files.

1. Clone or download the repository.
2. Open a terminal in the project directory.
3. Start a local HTTP server:

   ```bash
   python3 -m http.server 8000
   ```

4. Open [http://localhost:8000](http://localhost:8000) in your browser.

For an accurate local preview, check that the image and favicon paths in the HTML match the location of the files in `public/`.

## Deployment

The repository includes a `vercel.json` configuration. You can import the repository into Vercel and review the deployment settings before publishing. The site can also be hosted on a static website platform that supports HTML, CSS, and JavaScript.

Before deploying, verify that:

- All image and other asset paths resolve correctly.
- Every navigation link points to an existing page.
- The enquiry form successfully submits through Formspree.
- Phone and WhatsApp links use the intended contact details.
- The pages display correctly on desktop and mobile screens.

## Contact

For course or educational guidance enquiries, the website lists these contact channels:

- **Phone:** +91 82859 19263
- **Phone:** +91 93102 27258
- **Phone:** +91 72920 07680
- **Email:** [contactcoursecampus@gmail.com](mailto:contactcoursecampus@gmail.com)
- **WhatsApp:** [Chat with Course Campus](https://wa.me/918285919263)
- **Instagram:** [@coursecampusedu](https://www.instagram.com/coursecampusedu)
- **YouTube:** [Course Campus](https://www.youtube.com/@coursecampusedu)

**Address shown on the website:** 316/11 Shani Bazar, Bandh Road, Sangam Vihar, New Delhi 110080.

## Notes

Course details, eligibility, fees, admission dates, and recognition requirements can change. Visitors should confirm current requirements and final admission decisions directly with the relevant institution or official authority.
