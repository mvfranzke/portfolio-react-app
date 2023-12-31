# Portfolio
Personal portfolio created using REACT

## Description
This is the 20th assignment or challenge for our bootcamp class. Our assignment this week is to build our personal  single page portfolio showcasing our projects using REACT.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Credits](#credits)
- [License](#license)

## Installation

Create react file

```npx create-react-app .```

Install additional dependencies

```npm i react-icons```

```npm i react-scroll```

Follow steps below to edit action property in Components > Contact.jsx

Step 1. Create a free account in getform.io

Step 2. Click create, enter your application name and timezone

Step 3. Copy form endpoint link and enter inside ```<form action = " ">``` line 11

Add additional settings in package.json for deployment:

Set up homepage and set reference to your github repository, example below:

```  "homepage": "https://mvfranzke.github.io/portfolio-react-app",```

Create predeploy and deploy properties inside scripts:

  ```  "predeploy": "npm run build",```
  
 ```   "deploy": "gh-pages -d build",```

Finally, run ```npm run build``` and ```npm run deploy``` to update the site

## Usage

URL of Github repository : https://github.com/mvfranzke/Portfolio

URL of deployed application: https://mvfranzke.github.io/portfolio-react-app/

![home screenshot](src/assets/screenshot.jpg)

## User Story

```md
AS AN employer looking for candidates with experience building single-page applications
I WANT to view a potential employee's deployed React portfolio of work samples
SO THAT I can assess whether they're a good candidate for an open position
```

## Acceptance Criteria

```md
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
```

## Credits

Other resources used
* https://tailwindcss.com/docs/installation
* https://www.npmjs.com/package/react-icons
* https://www.npmjs.com/package/react-scroll?activeTab=readme
* https://create-react-app.dev/docs/deployment/

Used below links to resolve github deployment issue
* https://stackoverflow.com/questions/63964575/fatal-a-branch-named-gh-pages-already-exists
* https://dev.to/singhshemona/how-to-fix-only-the-readme-is-appearing-when-you-ve-deployed-to-github-pages-1ga3

Youtube Tutorials
* https://www.youtube.com/watch?v=bmpI252DmiI
* https://www.youtube.com/watch?v=22CxRxryQFE


## License
N/A

## Author

Created by Michelle von Franzke 🚀

[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/michelle-entico-006282190/)
&nbsp;
[![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/mvfranzke)

[back on top](#description)
