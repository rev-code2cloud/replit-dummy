# Project Documentation

## Pages Overview

In this project I am trying to create a replica of 'Replit.com'. It contains several HTML pages that are interconnected to provide a basic web experience. In this project I have used HTML and very basic CSS. CSS usuage is not as per the best practices, cause I am using CSS inline. Below is a summary of the main pages and their relationships.

### Main Page (`index.html`)

The homepage serves as the central hub linking to various features of the website:
- **Features**: Detailed description available at `pages/features.html`. Wanted to create a Drop down menu under the Features once the cursor hovers over it, but currently due to lack of knowledge in CSS, I am unable to do so.
- **Replit-AI**: Upcoming features page at `pages/comingsoon.html`.
- **Deployments**: Also links to `pages/comingsoon.html`
- **Teams**: Information about the team at `pages/teams.html`
- **Login**: User login page at `pages/login.html`. This is just the UI, no backend coding is done, basic html and css is used for its creation.
- **Point to Note**: All these links are created as 'nav' and not div for better SEO. Logo is linked to the landing page itself.

### Features Page (`pages/features.html`)

This page outlines the specific features offered by the website and links back to the homepage and other pages:
- **Logo**: It links to the landing page.
- **Login**
- **Features** (self-link)
- **Replit-AI**(coming soon)
- **Deployments**(coming soon)
- **Teams**
- **CDE** (coming soon)
- **Collaboration** (coming soon)

### Coming Soon Page (`pages/comingsoon.html`)

This is just a dummy page for all the features whose pages are to be designed. A placeholder for future content, this page has a link back to the homepage.

### Login Page (`pages/login.html`)

Handles user authentication and offers additional links. As of now it is not functional:
- **Forgot Password** (coming soon)
- **Sign Up** (coming soon)

### Teams Page (`pages/teams.html`)

This page is something which the Replit is going to launch, no clear understanding of it. Have just put the Image there. It includes links to:
- **Login**
- **Features**
- **Replit-AI**
- **Deployments**
- **Teams** (self-link)

## Navigation

Each page contains a navigation bar with links that provide easy access to all other pages in the project, ensuring a smooth and interconnected user experience.

## Images

Images used in the project are stored in the `images` directory and are incorporated throughout the various pages to enhance the visual appeal and user experience.

## Additional Notes

This README should be updated as new pages are added or existing pages are modified to ensure it accurately reflects the structure and navigation of the website.
