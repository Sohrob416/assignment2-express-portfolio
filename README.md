# Assignment 2 Express Portfolio

Sohrob Niazi  
Student ID: 100924971  
INFR3120 – Web and Scripting Programming

## About my project


This project is a portfolio about me I used Node.js, Express, and EJS to create my portfolio the pages home, about me, projects, and contact me.


## Running locally

Install the dependencies:

```powershell
npm.cmd install
```

Start the server:

```powershell
npm.cmd start
```

Open http://localhost:3000 in a browser.

## Project structure

- app.js configures Express, EJS, static files, and routers.
- bin/www starts the web server.
- routes/index.js contains the four portfolio routes.
- views contains the EJS page templates.
- views/partials contains the shared header, navigation, and footer.
- public/stylesheets/style.css contains the custom styling.
- public/bootstrap contains the Bootstrap assets.
- public/fontawesome contains the Font Awesome CSS and fonts.

## Routes

- /displays the Home page.
- /about displays the About Me page.
- /projects displays the Projects page.
- /contact displays the Contact Me page.

Each route calls res.render() to display an EJS view and passes
a title to that view. The views include the same header, navigation,
and footer to keep the layout consistent.

## Code sources and assistance


### Tools and libraries

- Express Generator created the initial application structure.
  https://expressjs.com/
- Bootstrap provides the navigation and container styling.
  https://getbootstrap.com/
- Font Awesome provides the navigation and GitHub icons.
  https://fontawesome.com/

Bootstrap and Font Awesome were installed through npm, and their
required assets were copied into the public folder.

### AI assistance

AI helped me with styling the websites looks, troubleshoot errors, organzing readme and grammer erros.

The email contact link uses mailto: to open a visitor's configured
email application.

## LinkedIn

My LinkedIn profile has my name, my school Ontario Tech University, what program im currently in
Networking and IT Security program, and the year I started.
https://www.linkedin.com/in/sohrob-niazi-a9184a44b/

## Deployment

The portfolio is hosted on Render.

Live website:
https://assignment2-express-portfolio-gysv.onrender.com/

GitHub repository:
https://github.com/Sohrob416/assignment2-express-portfolio
