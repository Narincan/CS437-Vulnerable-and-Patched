# CS437-Vulnerable-and-Patched
PHP-based news website fetching news from an RSS feed, with an admin panel for refreshing news. Includes two versions: vulnerable and patched. The project is containerized with Docker, using MySQL and Apache.

CS437S Cybersecurity Project - News Website with RSS Feed

This repository contains the source code for a news website built using PHP. The website fetches news from an RSS feed and includes an admin panel for refreshing news content. The project is designed for a cybersecurity course (CS437S) and features two versions of the website: one with security vulnerabilities and one with security patches applied.

The application is containerized using Docker, which includes MySQL as the database and Apache as the web server. This setup provides an isolated and reproducible environment to test both the vulnerable and secured versions of the site.

Key Features:

PHP-based website integrating with an RSS feed for real-time news updates.
Admin panel for easy management and refreshing of news content.
Two versions of the website:
Vulnerable: Includes common security flaws for learning purposes.
Patched: Fixes applied to address the vulnerabilities.
Dockerized setup with MySQL and Apache for easy deployment and testing.
Technologies:

PHP: Used for backend development and dynamic page rendering.
MySQL: Database management system used for storing news data.
Apache: Web server for serving the application.
Docker: Containerization tool for setting up a consistent development environment.
Setup Instructions:

Clone this repository to your local machine:
git clone <repo-url>
Navigate into the project directory:
cd <project-folder>
Build and start the Docker containers:
docker-compose up --build
Access the website in your browser at http://localhost.
You can view and test both the vulnerable and patched versions by accessing the respective directories.
License:

This project is for educational purposes only and is part of the CS437S Cybersecurity course.
