# Assignment 2 - Express Portfolio

This is my personal portfolio website for **INFR3120 - Web and Scripting Programming** at Ontario Tech University. It uses Node.js, Express, and EJS to display four pages about me and the projects I have worked on.

**Live site:** https://assignment-2-portfolio-4un6.onrender.com/

## Pages

- **Home (`/`)** - A short introduction to me and my interests in networking and IT security.
- **About Me (`/about`)** - My background, education, and interests.
- **Projects (`/projects`)** - Networking, web development, and website optimization projects.
- **Contact Me (`/contact`)** - Links to my email, LinkedIn, and GitHub.

## Technologies used

- **Node.js and Express.js** - Web server and routing
- **Express Generator** - Initial project folder structure
- **EJS** - Page templates and shared header/footer partials
- **Bootstrap 5** - Page layout and responsive styling
- **Font Awesome** - Icons
- **CSS** - Additional styling in `public/stylesheets/style.css`
- **Render** - Cloud hosting

## Project structure

```text
Assignment-2-portfolio/
├── app.js
├── bin/
│   └── www
├── public/
│   └── stylesheets/
│       └── style.css
├── routes/
│   └── index.js
├── views/
│   ├── partials/
│   │   ├── header.ejs
│   │   └── footer.ejs
│   ├── index.ejs
│   ├── about.ejs
│   ├── projects.ejs
│   ├── contact.ejs
│   └── error.ejs
├── package.json
└── package-lock.json
```

The Express Generator also created other starter files, such as `routes/users.js`.

## Running the site locally

Make sure Node.js and npm are installed. Then, from the project folder, run:

```bash
npm install
npm start
```

Open **http://localhost:3000** in a browser.

## How the site works

The `app.js` file sets EJS as the view engine and serves files from the `public` folder. The routes for all four portfolio pages are defined in `routes/index.js`. Each route uses `res.render()` to display its EJS page. The pages include shared navigation and footer files from `views/partials`.

## Sources and acknowledgements

The project structure and routing approach follow the Express Generator method covered in class. The site also uses the following tools and resources:

- [Express / Express Generator](https://expressjs.com/en/starter/generator.html) - Generated app structure
- [EJS](https://ejs.co/) - EJS template syntax and includes
- [Bootstrap 5](https://getbootstrap.com/) - CSS framework loaded through a CDN
- [Font Awesome](https://fontawesome.com/) - Icons loaded through a CDN

## AI assistance disclosure

I used **OpenAI ChatGPT (GPT-6, High thinking mode)** to help write and organize the text in this README file. The information here describes the files and features in this repository.
