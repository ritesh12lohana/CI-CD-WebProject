# PulseCode - Web Development Learning Platform

PulseCode is a responsive static website for a programming and web development learning platform. It is designed to help beginners explore courses related to web development, front-end development, back-end development, cloud computing, and Python.

The website is built using HTML, CSS, Bootstrap 5, and basic JavaScript. It includes multiple pages such as Home, About, Courses, and Contact. The homepage contains a responsive carousel and course cards, while the courses page displays course details in a structured table. The contact page includes a Formspree-powered form for user queries.

This project also includes a CI/CD pipeline using GitHub Actions. Whenever changes are pushed to the main branch, the workflow automatically deploys the website to an AWS S3 bucket. This demonstrates a basic but practical static website deployment workflow using modern DevOps practices.

## Features

- Responsive multi-page website
- Bootstrap navigation bar and carousel
- Course cards and course listing table
- Contact form using Formspree
- Light and dark mode toggle
- Custom CSS styling
- Accessible skip-to-content link
- AWS S3 deployment using GitHub Actions
- Automated CI/CD workflow on push to main branch

## Technologies Used

- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- GitHub Actions
- AWS S3
- Formspree

## Project Structure

```text
CI-CD-WebProject-main/
│
├── index.html
├── about.html
├── courses.html
├── contact.html
├── styles.css
├── video.mp4
├── images
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml
