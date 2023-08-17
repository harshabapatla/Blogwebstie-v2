# Blogwebstie-v2
This version of blog website connects with MongoDB
# Simple Blogging Web Application

Welcome to the Simple Blogging Web Application! This application allows users to create, view, and read blog posts. It is built using Express.js and MongoDB, making it a powerful tool for managing and sharing your thoughts.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Endpoints (Routes)](#endpoints-routes)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This web application provides a platform for users to create and publish their blog posts. Users can compose new posts, view existing posts, and learn more about the project's creators. The application is designed to be simple, user-friendly, and easy to set up.

## Features

- Create new blog posts with titles and content.
- View a list of all blog posts on the home page.
- Read individual blog posts in a detailed view.
- Learn more about the project and its creators through the "About" page.
- Find contact information on the "Contact" page.

## Installation

1. Make sure you have Node.js and npm installed on your machine.
2. Clone this repository to your local machine: `git clone https://github.com/yourusername/your-repo.git`
3. Navigate to the project directory: `cd your-repo`
4. Install project dependencies: `npm install`
5. Set up your MongoDB connection string in the `app.js` file.

## Usage

1. Start the application by running: `npm start`
2. Access the application in your web browser at: `http://localhost:3000`
3. Create new blog posts by visiting the "Compose" page.
4. Read and explore existing blog posts on the home page.
5. Learn more about the project and its creators on the "About" and "Contact" pages.

## File Structure

- `app.js`: Main application file
- `views/`: Contains EJS templates for different pages
- `public/`: Stores static assets such as CSS and images

## Dependencies

- Express
- EJS
- Body-parser
- Mongoose

## Configuration

Create a `.env` file in the project root and add your MongoDB connection URI:


## Endpoints (Routes)

- `/`: Home page showing a list of blog posts
- `/about`: About page with project information
- `/contact`: Contact page for getting in touch
- `/compose`: Create a new blog post
- `/posts/:postId`: View a specific blog post

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow the guidelines in the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or feedback, feel free to reach out to hbapatla@asu.edu.
