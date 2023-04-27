# Portfolio-Upgrade --> React Challenge: React Portfolio

Being a web developer means being part of a community. You’ll need a place to share your projects not only if you're applying for jobs or working as a freelancer but also so that you can share your work with fellow developers and collaborate on future projects.

Now that you’ve completed multiple projects, your task is to create a portfolio, using your new React skills to help set you apart from other developers whose portfolios don’t use the latest technologies.

Just as you did in the module project, you’ll need to deploy this application to GitHub Pages. Follow the same instructions that you did for the project to create a build that you can deploy.

## User Story

AS AN employer looking for candidates with experience building single-page applications
I WANT to view a potential employee's deployed React portfolio of work samples
SO THAT I can assess whether they're a good candidate for an open position

## Acceptance Criteria

GIVEN a single-page application portfolio for a web developer
WHEN I load the portfolio
THEN I am presented with a page containing a header, a section for content, and a footer
WHEN I view the header
THEN I am presented with the developer's name and navigation with titles corresponding to different sections of the portfolio
WHEN I view the navigation titles
THEN I am presented with the titles About Me, Portfolio, Contact, and Resume, and the title corresponding to the current section is highlighted
WHEN I click on a navigation title
THEN I am presented with the corresponding section below the navigation without the page reloading and that title is highlighted
WHEN I load the portfolio the first time
THEN the About Me title and section are selected by default
WHEN I am presented with the About Me section
THEN I see a recent photo or avatar of the developer and a short bio about them
WHEN I am presented with the Portfolio section
THEN I see titled images of six of the developer’s applications with links to both the deployed applications and the corresponding GitHub repository
WHEN I am presented with the Contact section
THEN I see a contact form with fields for a name, an email address, and a message
WHEN I move my cursor out of one of the form fields without entering text
THEN I receive a notification that this field is required
WHEN I enter text into the email address field
THEN I receive a notification if I have entered an invalid email address
WHEN I am presented with the Resume section
THEN I see a link to a downloadable resume and a list of the developer’s proficiencies
WHEN I view the footer
THEN I am presented with text or icon links to the developer’s GitHub and LinkedIn profiles, and their profile on a third platform (Stack Overflow, Twitter) 

## Getting Started

The application that you built for this module will help you know where to start when building your portfolio. You’ll use Create React App just as you did with your module project, but you should be aware of a few structural differences in the component hierarchy. Your portfolio should include the following:

- A single Header component that appears on multiple pages
- A single Navigation component within the header that will be used to conditionally render the different sections of your portfolio
- A single Project component that will be used multiple times in the Portfolio section
- A single Footer component that appears on multiple pages

## Projects

For each project you feature in your portfolio, you should include the following:

- An image of the deployed application (either a GIF or a screenshot)
- The title of the project
- A link to the deployed application
- A link to the corresponding GitHub repository

## Design

As with the previous portfolio Challenge, remember that "good" design is subjective; however, your site should look polished. Here are a few guidelines on what that means:

- Use mobile-first design.
- Choose a color palette so that your site doesn't just look like the default Bootstrap theme or an unstyled HTML site. Look into resources like Coolors <https://coolors.co/> or another color scheme generator to help you create something that will stand out.
- Make sure the font size is large enough to read and that the colors don't cause eye strain.
- Consider using animations and React component libraries. Note that this will not affect your grade, but it may impact how potential employers gauge your knowledge.

### Base File Structure (npx create-react-app react-portfolio?)

react-portfolio/
│
├── public/
│   ├── index.html
│   └── ...
│
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── Navigation.js
│   │   ├── About.js
│   │   ├── Portfolio.js
│   │   ├── Project.js
│   │   ├── Contact.js
│   │   ├── Resume.js
│   │   └── Footer.js
│   ├── App.js
│   ├── index.js
│   ├── styles/
│   │   ├── Header.css
│   │   ├── Navigation.css
│   │   ├── About.css
│   │   ├── Portfolio.css
│   │   ├── Project.css
│   │   ├── Contact.css
│   │   ├── Resume.css
│   │   └── Footer.css
│   └── assets/
│       ├── images/
│       │   ├── project1.jpg
│       │   ├── project2.jpg
│       │   ├── ...
│       │   └── avatar.jpg
│       └── resume.pdf
│
├── .gitignore
├── package.json
└── README.md
