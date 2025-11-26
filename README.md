# Lukas Weissenhorn - Personal Website

A lightweight, semantic, and responsive personal portfolio website. This project is designed to be simple, fast, and easily deployable.

## 🚀 About
This repository contains the source code for my personal landing page. It serves as a digital business card, showcasing my background as a Software Engineer, my tech stack, and contact information.

**Focus:**
*   Semantic HTML5 structure
*   Clean CSS (No heavy frameworks)
*   Containerized deployment via Docker + Nginx

## 🛠️ Tech Stack
*   **Frontend:** HTML5, CSS3
*   **Deployment:** Docker, Nginx (Alpine Linux)

## 🐳 How to Run

### Option 1: Docker (Recommended)
This project includes a `Dockerfile` to serve the static content using a lightweight Nginx server.

1.  **Build the image:**
    ```bash
    docker build -t lukas-website .
    ```

2.  **Run the container:**
    ```bash
    docker run -d -p 8080:80 --name my-site lukas-website
    ```

3.  **View the site:**
    Open [http://localhost:8080](http://localhost:8080) in your browser.

### Option 2: Local Files
Simply clone the repository and open the `index.html` file in any web browser.

## 📂 Project Structure
```text
.
├── assets/          # Images and favicon
├── css/             # Styles
