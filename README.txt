# Arwa Mahmood | Portfolio

A modern, responsive portfolio website for **Arwa Mahmood**, a React / Frontend Developer and BSCS student. It presents my projects, skills, and contact details to recruiters and potential freelance clients.

## 🚀 About the Project

The portfolio is a single-page website with a dark blue theme, light blue highlights, and a blue glow on hover. It is built with plain HTML, CSS, and JavaScript, so there is nothing to install.

Sections:

* Animated loader with my name
* Home with headline and call-to-action buttons
* About me with photo
* Featured projects (web applications and websites) with image previews, live demos, and source code links
* Technical skills
* Services
* How I work
* Contact section with direct email, LinkedIn, GitHub, and a project enquiry form

## 🛠️ Technologies Used

* HTML5
* CSS3 (Flexbox, Grid, animations, responsive layout)
* JavaScript (vanilla, no libraries)
* HTML Canvas (animated metallic star background)
* Git & GitHub

No frameworks, build tools, or package managers are required.

## ✨ Features

* Animated loader that shows my name
* Sticky navigation bar with a "Hire Me" button and a mobile menu
* Metallic star background drawn on canvas
* Scroll reveal animations
* Project cards with image previews, hover glow, **Live Demo** and **Source Code** buttons
* Projects split into separate horizontally scrollable rows: Web Applications and Websites
* Skills, services, and process cards displayed in a single scrollable row
* Contact form that opens the visitor's email app with their details filled in
* Responsive layout for desktop, tablet, and mobile

## 📂 Project Structure

```text
arwa-portfolio/
│
├── index.html
├── README.md
│
└── images/
    ├── Picture.png
    └── projects/
        ├── buildcv.png
        ├── freelancer-workspace.png
        ├── wordvault.png
        ├── luxestate.png
        ├── luxury-salon.png
        └── powerfit.png
```

If a project preview image is missing, the card shows the project's colored initials instead.

## 💻 Getting Started

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Add your images

* Put your profile photo at `images/Picture.png`
* Put one screenshot per project in `images/projects/` using the file names shown above

### 3. Run the website

Open `index.html` in your browser.

For a better development experience, use the **Live Server** extension in VS Code.

## 🎨 Customization

* **Colors:** Edit the variables in the `:root` block at the top of the `<style>` section (`--bg`, `--accent`, `--gray`).
* **Projects:** Copy any `<article class="card proj">` block to add a project, then change its name, description, image, and links.
* **Loader time:** Change the `2600` value (milliseconds) in the script.
* **Contact form:** It uses a `mailto:` link, so it opens the visitor's email app. Change the email address in the script and in the contact section.

## 📌 Projects

### Web Applications

| Project | Description | Live Demo | Source |
| --- | --- | --- | --- |
| BuildCV | Resume builder with 24 free templates, preview, and PDF export (React, Tailwind CSS, GSAP) | [Demo](https://build-cv-app-phi.vercel.app) | [GitHub](https://github.com/Arvaa11/BuildCV-App) |
| Freelancer Workspace | Productivity dashboard for organizing freelancer tasks and work | [Demo](https://freelancer-workspace-six.vercel.app) | [GitHub](https://github.com/Arvaa11/Freelancer-Workspace) |
| WordVault | Vocabulary app for managing and practicing words, saved in browser localStorage (React) | [Demo](https://word-vault-app.vercel.app) | [GitHub](https://github.com/Arvaa11/WordVault-App) |

### Websites

| Project | Description | Live Demo | Source |
| --- | --- | --- | --- |
| LuxEstate | Real estate website | [Demo](https://lux-estate-eosin.vercel.app) | [GitHub](https://github.com/Arvaa11/LuxEstate) |
| Luxury Beauty Salon | Beauty salon website | [Demo](https://arvaa11.github.io/Luxury-Beauty-Salon-Website) | [GitHub](https://github.com/Arvaa11/Luxury-Beauty-Salon-Website) |
| PowerFit GYM | Fitness website | [Demo](https://arvaa11.github.io/PowerFit-GYM) | [GitHub](https://github.com/Arvaa11/PowerFit-GYM) |

## 🧰 Skills Shown in the Portfolio

* **Frontend:** HTML5, CSS3, JavaScript, React.js, TypeScript, Tailwind CSS, Responsive Web Design
* **Motion and interaction:** GSAP, GSAP ScrollTrigger
* **Workflow:** Git, GitHub
* **Currently learning:** Node.js, Express.js, REST APIs, PostgreSQL, MySQL

## 🔮 Future Improvements

* Add more projects and real screenshots
* Improve animations and interactions
* Add more accessibility improvements
* Add new sections as my skills and experience grow

## 👩‍💻 Author

**Arwa Mahmood**

React Developer / Frontend Developer · BSCS Student

I build useful web applications with React, focusing on practical tools, dashboards, clean interfaces, and thoughtful user experiences.

* LinkedIn: [arwa-mahmood-45198939a](https://www.linkedin.com/in/arwa-mahmood-45198939a/)
* GitHub: [Arvaa11](https://github.com/Arvaa11)
* Email: arvaamehmood11@gmail.com

---

⭐ If you find this portfolio interesting, feel free to explore the repository and check out my projects.