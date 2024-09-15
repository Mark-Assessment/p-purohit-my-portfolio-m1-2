# Full Stack Developer Portfolio Website:  
---                           
![Image Alt](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/Responsive%20p-1.png?raw=true)
Website Link :
[https://purohit1999.github.io/Porject_My-Portfolio/](https://purohit1999.github.io/Porject_My-Portfolio/)

Welcome to the Full Stack Developer Portfolio project! This repository contains the source code and documentation for a personal portfolio website showcasing the skills and services of a full stack developer. This README provides an overview of the project, including its features, technologies used, testing, deployment, and more.

## Table of Contents
1. [Project Overview](#project-overview)
2. [UX/UI Design](#uxui-design)
    - [Project Goals](#project-goals)
    - [User Goals](#user-goals)
    - [Parental Goals](#parental-goals)
    - [Developer and Business Goals](#developer-and-business-goals)
3. [Colour Scheme](#colour-scheme)
4. [Typography](#typography)
5. [User Stories](#user-stories)
6. [Imagery](#imagery)
7. [Wireframes](#wireframes)
8. [2D Skeleton Models](#2d-skeleton-models)
    - [Mobile View](#mobile-view)
    - [Tablet View](#tablet-view)
    - [Desktop View](#desktop-view)
9. [Design Choices](#design-choices)
    - [Mobiles](#mobiles)
    - [Tablets](#tablets)
    - [Desktops](#desktops)
10. [Features](#features)
    - [Features Left to Implement](#features-left-to-implement)
11. [Technologies Used](#technologies-used)
12. [Testing](#testing)
    - [W3C Markup Validator](#w3c-markup-validator)
    - [W3C CSS Validator](#w3c-css-validator)
    - [Testing User Stories from User Experience (UX) Section](#testing-user-stories-from-user-experience-ux-section)
    - [First Time Visitors Goals](#first-time-visitors-goals)
    - [Returning Visitor Goals](#returning-visitor-goals)
    - [Frequent User Goals](#frequent-user-goals)
    - [Lighthouse](#lighthouse)
    - [Manual Testing](#manual-testing)
    - [Solved Bugs](#solved-bugs)
    - [Unit Testing](#unit-testing)
    - [Further Testing](#further-testing)
13. [File Overview](#file-overview)
    - [index.html](#indexhtml)
    - [style.css](#stylecss)
14. [Deployment](#deployment)
    - [GitHub Pages](#github-pages)
    - [Forking the GitHub Repository](#forking-the-github-repository)
    - [Making a Local Clone](#making-a-local-clone)
15. [Credit](#credit)
16. [Content](#content)
17. [Media](#media)
18. [Acknowledgements](#acknowledgements)

## Project Overview
The Full Stack Developer Portfolio is a responsive website that highlights the developer's expertise in front-end and back-end development, UI/UX design, and more. It serves as a professional platform to attract potential clients and collaborators.

## UX/UI Design

### Project Goals
- Create a professional portfolio website to showcase development skills.
- Attract potential clients and collaborators.

### User Goals
- Easily navigate and find information about services and projects.
- Contact the developer for collaboration or inquiries.

### Parental Goals
- Ensure the website is safe and appropriate for all audiences.

### Developer and Business Goals
- Demonstrate expertise in full stack development.
- Highlight past projects and testimonials to build credibility.

## Colour Scheme
Created a color scheme for portfolio website involves choosing a palette that reflects your personal style while ensuring readability and aesthetic appeal.The three main colors used are Code Institute Blue, red, and white.

- ### Primary Color 

Hex Code: #1E3A8A
Color: Deep Blue
Usage: This color can be used for headers, navigation bar, and other primary elements like buttons and links. It gives a professional and modern look.

- ### Secondary Color 

Hex Code: #22D3EE
Color: Cyan
Usage: Ideal for highlighting important sections, secondary buttons, and icons. It pairs well with deep blue to create a dynamic contrast.

- ### Background Color 

Hex Code: #F9FAFB
Color: Light Gray
Usage: Use this as the main background color to ensure content readability and a clean, minimalist appearance.

- ### Accent Color 

Hex Code: #F59E0B
Color: Amber
Usage: Use this color for accents like hover states, call-to-action buttons, and other interactive elements to draw attention.

- ### Text Color 

Hex Code: #111827
Color: Charcoal Black
Usage: Use this color for primary text. It ensures high readability against the light gray background.

- ### Secondary Text Color 

Hex Code: #4B5563
Color: Cool Gray
Usage: Use this for secondary text, such as subtitles or descriptions, providing a softer contrast against the background.

- ### Border/Divider Color 

Hex Code: #D1D5DB
Color: Light Gray
Usage: For borders, dividers, and subtle lines, this color will maintain the minimalist feel without being too bold. 

## Typography
The Roboto font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Roboto is a clean font used frequently in programming, so it is both attractive and appropriate.

## User Stories  
### 1. As a potential client, I want to see testimonials for examples of past work.
- **Description**: The "Testimonials" section is designed to prominently display client feedback and endorsements. This helps potential clients evaluate the developer's skills and reliability.  

  - The testimonials are easily accessible from the homepage.
  - Each testimonial includes a client name and their feedback.
  - The section is visually appealing with a clean design.
- **Screenshot:**
---
![Testimonials Section](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/user_story1.png?raw=true)

### 2. As a visitor, I want to easily find contact information to get in touch with the developer.
- **Description**: The "Contact Us" section includes a form, email address, and phone number. This ensures visitors can reach out easily.
- **Acceptance Criteria**:
  - Contact form fields are clearly labeled and functional.
  - Contact information is prominently displayed.
  - The form includes validation to ensure accurate submissions.
- **Screenshot:**
---
![Contact Form](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/contact_form.png?raw=true)

### 3. As a user, I want a responsive and visually appealing website experience.
- **Description**: The website is designed to be responsive, ensuring a smooth experience across all devices (mobile, tablet, and desktop).
- **Acceptance Criteria**:
  - The layout adjusts to different screen sizes.
  - All interactive elements remain accessible and functional.
  - Visual appeal is maintained across all devices.
- **Screenshot:**
---
![Responsive Design](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/user_story2.png?raw=true)

### 4. As a user, I want to be able to return to the home page after completing a form submission.
- **Description**: After submitting the contact form, users are redirected to the homepage, which confirms the successful submission.
- **Acceptance Criteria**:
  - Users receive a confirmation message.
  - Users are redirected to the homepage.
  - The homepage displays a success message or confirmation of the submission.
- **Screenshot:**
---
![Confirmation Message](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/confirmation_message.png?raw=true)

### 5. As a user, I want the webpage to be responsive and accessible on any device.
- **Description**: The website maintains functionality and readability across various devices, including mobile phones, tablets, and desktops.
- **Acceptance Criteria**:
  - The design adapts to different screen sizes.
  - Touch and interaction elements are usable on mobile devices.
  - The layout remains consistent and user-friendly.
- **Screenshot:**
---
![Responsive Layout](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/responsive_layout.png?raw=true)  

## Imagery
Imagery is important. The large MS AI-created, background hero image is designed to be striking and catch the user's attention. It also has a modern, energetic aesthetic. [Here link](https://www.bing.com/images/create/)

## Wireframes
Wireframes are included as part of the design documentation below :  
[Here Link](https://app.diagrams.net/)  

[Here Link](https://balsamiq.com/)


## 2D Skeleton Models

### Mobile View
|-----------------------|
|       Navbar          |
|-----------------------|
|     Hero Section      |
|-----------------------|
|     Services          |
|-----------------------|
|     Projects          |
|-----------------------|
|     Testimonials      |
|-----------------------|
|     Contact Us        |
|-----------------------|
|       Footer          |
|-----------------------|
---

![Image Alt](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/Mobile%20UI-UX.png?raw=true)
---




### Tablet View
|------------------------------------------------|
|                    Navbar                      |
|------------------------------------------------|
|                 Hero Section                   |
|------------------------------------------------|
|                   Services                     |
|------------------------------------------------|
|                   Projects                     |
|------------------------------------------------|
|                 Testimonials                   |
|------------------------------------------------|
|                 Contact Us                     |
|------------------------------------------------|
|                    Footer                      |
|------------------------------------------------|
---

![Image Alt](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/Tablet%20View.png?raw=true)
---

### Desktop View
|----------------------------------------------------------------------------------|
|                                    Navbar                                        |
|----------------------------------------------------------------------------------|
|                                Hero Section                                      |
|----------------------------------------------------------------------------------|
|                                  Services                                        |
|----------------------------------------------------------------------------------|
|                                  Projects                                        |
|----------------------------------------------------------------------------------|
|                                Testimonials                                      |
|----------------------------------------------------------------------------------|
|                                Contact Us                                        |
|----------------------------------------------------------------------------------|
|                                    Footer                                        |
|----------------------------------------------------------------------------------|
---

![Image Alt](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/Desktop%20View.png?raw=true)
---

## Design Choices
- Clean and modern design with intuitive navigation.
- Use of Bootstrap for responsive layout.
- High-quality images and clear typography.

### Mobiles
- Single-column layout with collapsible navbar.

### Tablets
- Two-column layout with more space for images and text.

### Desktops
- Multi-column layout with larger images and more detailed sections.

## Features
- Responsive Design: Ensures optimal viewing experience on all devices.
- Hero Section: Eye-catching introduction with call-to-action.
- Services Section: Overview of the services offered.
- Projects Section: Showcases past work with descriptions.
- Testimonials: Client feedback and endorsements.
- Contact Form: Easy way for users to get in touch.
- Footer: Links to social media and additional information.

### Features Left to Implement
- Blog Section: Share articles and insights.
- Portfolio Filtering: Allow users to filter projects by category.
- Live Chat: Real-time communication with visitors.

## Technologies Used
- HTML5: Structure and content of the website.
- CSS3: Styling and layout.
- Bootstrap: Responsive design framework.
- JavaScript: Interactive elements and functionality.
- Font Awesome: Icons.
- Google Fonts: Typography.

### Frameworks, Libraries & Programs Used
- Bootstrap 4.4.1: Used to assist with the responsiveness and styling of the website.
- Hover.css: Used on the Social Media icons in the footer to add the float transition while being hovered over.
- Google Fonts: Used to import the 'Titillium Web' font into the style.css file.
- Font Awesome: Used on all pages throughout the website to add icons for aesthetic and UX purposes.
- jQuery: Came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
- Git: Used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
- GitHub: Used to store the project's code after being pushed from Git.
- Photoshop: Used to create the logo, resizing images, and editing photos for the website.
- Balsamiq: Used to create the wireframes during the design process.

## Testing
The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors.

### W3C Markup Validator :
Results : 
![Image Alt](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/html_validation.png?raw=true)
---


### W3C CSS Validator :    
Results :
![Image Alt](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/css_validation.png?raw=true)
---

### Testing User Stories from User Experience (UX) Section

### First Time Visitors Goals
- **Introduction**: The homepage provides a clear and concise introduction, immediately highlighting my key services as a front-end and back-end developer, ensuring first-time visitors understand the scope of my offerings.
- **Engagement**: The design is visually appealing, with a clean, professional layout and engaging visuals that capture the visitor's attention. Clear headings and a consistent color scheme guide the user's focus.
- **Navigation**: The site’s navigation is simple and intuitive, allowing users to easily explore the services, about section, and contact information through a well-structured menu.
- **Call to Action**: Multiple call-to-action buttons encourage visitors to get in touch via the contact form or learn more about my services, fostering engagement from the outset.

### Screenshot:

![First Time Visitors Screenshot](https://purohit1999.github.io/Porject_My-Portfolio/assets/images/first-user-story.png)
---

### Returning Visitor Goals
- **Re-engagement**: Clear, accessible links to detailed service pages, such as Front-End and Back-End Development, allow returning visitors to quickly find the information they need.
- **Updates**: Regularly updated projects and testimonials are prominently displayed, ensuring returning visitors can see new work and stay engaged with the latest content.
- **Conversion**: The site encourages returning visitors to reach out for consultations or inquiries through the contact page and strategically placed call-to-action buttons throughout the site.  

### Screenshot:

![Second Time Visitors Screenshot](https://purohit1999.github.io/Porject_My-Portfolio/assets/images/screenshot.png)
---

### Frequent User Goals
- **Resource Access**: Frequent users have direct access to the most relevant pages through the easy-to-navigate menu, providing quick links to specific services they seek.
- **Trust Building**: Testimonials and case studies are updated frequently, building trust and credibility with users who return to the site.
- **Community Engagement**: Social media links are integrated to encourage ongoing interaction and keep users connected with the latest updates and content from my portfolio.  

### Screenshot:

![Third Time Visitors Screenshot](https://purohit1999.github.io/Porject_My-Portfolio/assets/images/screenshot.png)
---

### Lighthouse
Used Chrome Developer Tools Lighthouse to test site performance, best practices, and accessibility. 
---

![Image Alt](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/Lighthouse_testing.png?raw=true)


### Manual Testing
- **Navigation Links**: Ensured all links work correctly.
- **Responsive Design**: Tested on various devices and screen sizes.
- **Form Functionality**: Tested contact form submission.
- **Browsers Tested:** Chrome, Firefox, Safari, Edge
- **Devices Tested:** Desktop, Tablet, Mobile  
---
![Image Alt](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/validation_form.png?raw=true)

### Solved Bugs  
I wanted to bring to your attention an ongoing issue related to my GitHub account that is affecting the visibility of my P-1 project. Despite having made 20 commits (please find the enclosed screenshot), the page is still not accessible to tutors, mentors, or yourself. This is the same issue we encountered when I initially submitted the project.  

During a recent tutoring session with Sara, we discussed this problem, and she suggested that I work from a new GitHub profile. Consequently, I transitioned my work from my previous profile (param155) to a new one (Purohit1999). Unfortunately, this means that the commits made under my old profile are not reflected on my new one. Additionally, I primarily use VS Code for my development work due to the slow performance of Gitpod, which significantly impacts my efficiency.  

It appears that there might be a configuration issue with my student account on the Code Institute platform. My mentor also believes that this is the case, as the project remains inaccessible despite being public. I kindly request that you liaise with the appropriate team at Code Institute to resolve this matter, as I have invested a considerable amount of time in ensuring that my P-1 project is both attractive and responsive.   
---
![Image Alt](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/P-1%2020COMMITS.png?raw=true)      
- **Custom Modal Opacity Issue**: Fixed by adjusting CSS properties.
- **Footer Social Media Not Centered**: `justify-content: center;` applied.  
---  
  ![Image Alt](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/bug4.png?raw=true)  

  - **Bug:** Navigation bar not responsive on mobile view.
  - **Solution:** Adjusted CSS media queries to ensure proper scaling.  

- **Bug:** Contact form submission failed.
  - **Solution:** Fixed JavaScript validation errors and server-side handling.  


### Unit Testing
- **JavaScript Functions**: Ensured all custom scripts work as expected.  
- **Coverage:** Tested individual components and their functionality using Jest and other testing frameworks.

### Further Testing
- **Usability Testing**: Conduct tests to ensure ease of navigation, especially for first-time visitors.
- **Performance Testing**: Ensure the webpage loads quickly across all devices, particularly mobile.
- **A/B Testing**: Experiment with different call-to-action placements, button colors, and hero section layouts to maximize engagement.
- **Accessibility Testing**: Verify that the website meets accessibility standards (e.g., contrast ratios, alt texts, etc.).
---

  ![Image Alt](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/Desktop%20page%20Speed%20P-1.png?raw=true)
  ---
  ![Image Alt](https://github.com/Purohit1999/Porject_My-Portfolio/blob/main/assets/Mobile%20Page%20Speed%20P-1.png?raw=true)  
  ---



### **Testing Matrix**

| **Validations**  | **Results** |
|------------------|-------------|
| **HTML**         | Passed (No errors or warnings) |
| **CSS**          | Passed (No errors found) |

| **Responsiveness**                              | **Pixel 5** | **Galaxy S8+** | **iPhone 11** | **iPad Mini** | **iPad Air** | **Surface Pro** | **Desktop 1024px+** | **Desktop 1280px+** | **iMac 1900px+** |
|-------------------------------------------------|-------------|----------------|---------------|---------------|--------------|-----------------|---------------------|---------------------|-------------------|
| Responsive devices with width of 375px or more  | Good        | Good           | Good          | n/a           | Good         | n/a             | Good                | Good                | Good              |
| Responsive devices with width of 768px or more  | n/a         | Good           | Good          | n/a           | Good         | Good            | Good                | Good                | Good              |
| Responsive devices with width of 1024px or more | n/a         | Good           | Good          | n/a           | n/a          | Good            | Good                | Good                | Good              |
| Internal Links Work                             | Good        | Good           | Good          | Good          | Good         | Good            | Good                | Good                | Good              |
| External Links Open in New Tab                  | Good        | Good           | Good          | Good          | Good         | Good            | Good                | Good                | Good              |
| Images not pixelated or stretched               | Good        | Good           | Good          | Good          | Good         | Good            | Good                | Good                | Good              |

| **Browser Compatibility**   | **Chrome** | **Safari** | **Firefox** | **Edge** |
|-----------------------------|------------|------------|-------------|----------|
| Appearance                  | Good       | Good       | Good        | Good     |
| Responsiveness              | Good       | Good       | Good        | Good     |

### **Notes:**
- Testing conducted across a variety of devices and browsers.
- HTML and CSS validations passed successfully.
- Responsiveness and appearance were consistently good across all tested devices and browsers.  
This matrix illustrate the successful validation and responsiveness testing across multiple devices and browsers.  

---

## File Overview

### index.html
This file contains the structure and content of the webpage. Key sections include:  
- **Purpose:** Main HTML file containing the structure and content of the website.
- **Head**: Contains metadata, links to Bootstrap for styling, and a FontAwesome kit for icons.
- **Navbar**: A responsive navigation bar with links to key sections (Home, Services, Contact).
- **Hero Section**: Introduces the Full Stack Developer and includes a call-to-action button.
- **Services Section**: Lists key services with brief descriptions and links to more detailed pages.
- **Black Box Section**: A prominent call-to-action inviting visitors to discuss their project ideas.
- **Work Section**: Showcases specific services with cards that provide more detailed descriptions.
- **Testimonials**: A carousel of client testimonials to build trust with new and returning visitors.
- **Contact Section**: Provides a contact form and details about how to get in touch, along with an About Us section.
- **Footer**: Contains quick links, a brief about the developer, and social media icons for connection.
---

### style.css
This file provides the styling for the webpage. Key styles include:  
- **Purpose:** CSS file for styling the website, including layout, colors, and typography.
- **Fonts**: The webpage uses the "Roboto" font family.
- **Hero Section**: Custom styles for background image, text positioning, and the glowing button effect.
- **Responsive Design**: Media queries ensure that the site looks good on different screen sizes.
- **Banner Section**: Styles the service buttons and their hover effects.
- **Card Components**: Ensures consistent card layout with hover effects for service offerings.
- **Footer**: Styles for footer sections including social media icons and responsive adjustments.
---

## Deployment

### GitHub Pages
The project was deployed to GitHub Pages using the following steps:
1. Log in to GitHub and locate the GitHub Repository.
2. At the top of the Repository, locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.  

---

### Forking the GitHub Repository
Forking the GitHub Repository allows you to make a copy of the original repository on your GitHub account. Steps to fork the repository:
1. Log in to GitHub and locate the GitHub Repository.
2. At the top of the Repository, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.
---

### Making a Local Clone
1. Log in to GitHub and locate the GitHub Repository.
2. Under the repository name, click "Clone or download".
3. Copy the link under "Clone with HTTPS".
4. Open Git Bash.
5. Change the current working directory to the location where you want the cloned directory.
6. Type `git clone`, and then paste the URL you copied in Step 3.
7. Press Enter. Your local clone will be created.
---

## GitPod and GitHub Deployment Issues Resolved  
Over the past three days, I have been diligently working on my first project, which is now complete and functioning perfectly in Visual Studio. However, when attempting to share my project with the online tutors for review, they are unable to access my GitHub profile. This issue is severely hampering my progress as I am unable to receive the necessary feedback and move forward to the JavaScript lessons.

Despite multiple attempts to resolve this issue, including extensive troubleshooting on SLACK and seeking help from the online tutors, the problem remains unresolved. I am now reaching out to you as my last resort, hoping for a swift resolution.

The main issues I am encountering are as follows:

**GitHub Profile Visibility**: My online tutors are unable to view my GitHub profile and the project repository, which is essential for them to review my work.

**GitPod Accessibility**: There seem to be issues with GitPod that are preventing my project from being accessed and reviewed online.

Given that I have already invested a considerable amount of time and effort into resolving these issues without success, I kindly request your immediate assistance in addressing and resolving these problems. It is crucial for me to submit my project promptly and continue with the coursework as scheduled.

Please let me know if you require any additional information or access details to diagnose and fix the issues. Your prompt attention to this matter would be greatly appreciated.  

---

## Credit
- The full-screen hero image code came from a StackOverflow post.
- **Bootstrap 4**: Used throughout the project to make the site responsive using the Bootstrap Grid System.
- **MDN Web Docs**: For Pattern Validation code. Code was modified to fit a UK phone number layout.
---
### Media
- All Images were created by the developer using Bing's free AI tool.
- Free Images source:
  - [Bing Image](https://www.bing.com/images/create/coding/1-669fa5b21f484aef93025d5b052fbaf6?id=zKwrjxoByUGzIp7O4qqoSw%3d%3d&view=detailv2&idpp=genimg&thId=OIG4.ZHZnpIySJoQ.yBTGIOI4&FORM=GCRIDP&ajaxhist=0&ajaxserp=0)
---
### Free Fonts source
- [Roboto](https://fonts.google.com/specimen/Roboto)
- [Font Awesome](https://fontawesome.com/kits)
---
### Code
- **Bootstrap** components and **Font Awesome** icons.
  - [Get Bootstrap](https://getbootstrap.com/)
  - [Google Fonts - Roboto](https://fonts.google.com/specimen/Roboto)
---  

## Content
All content was written by the developer. Psychological properties of colors text in the README.md was found on the Colour Affects website.  

---

## Acknowledgements
- My Mentor for continuous helpful feedback.
- Tutor support at Code Institute for their support.
- EKC college teacher Rachel Furlong's help and support.
