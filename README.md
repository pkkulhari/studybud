<!-- LOGO -->
<br />
<div align="center">
  <a href="https://github.com/pkkulhari/studybud">
    <img src="static/img/logo.svg" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Studybud</h3>

  <p align="center">
    Simple Web App Like Discord Server
    <br />
    <a href="https://github.com/pkkulhari/studybud/README.md"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://studybud1.herokuapp.com/">View Demo</a>
    ·
    <a href="https://github.com/pkkulhari/studybud/issues">Report Bug</a>
    ·
    <a href="https://github.com/pkkulhari/studybud/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

[![Product Name Screen Shot][product-screenshot]](https://studybud1.herokuapp.com/)

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

- [Django](https://www.djangoproject.com/)
- Postgres
- HTML & CSS
- JavaScript

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

To setup a development environment, you are required `Python` with `pip`, Secondly create a account (free plan) on [Cloudinary](cloudinary.com) and get your `CLOUD_NAME`, `API_KEY` and `API_SECRET`

- pip

  ```sh
  pip install --upgrade pip
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/pkkulhari/studybud.git
   ```
2. Change the dir to **studybud** and install pip packages
   ```sh
   cd studybud && pip install -r requirements.txt
   ```
3. rename `.env-example` file to `.env` (Don't forget to replace dummy cloudinary credentials with yours in `.env` file)
   ```sh
   mv ./.env-example ./.env
   ```
4. perform DB migrations
   ```sh
   python manage.py migrate
   ```
5. Finally, start the app by spinning up django dev server
   ```sh
   python manage.py runserver
   ```

Now, the app should listening on http://127.0.0.1:8000/

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[product-screenshot]: static/img/screenshot.png
