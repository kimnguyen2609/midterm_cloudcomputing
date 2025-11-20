# Cloud Computing Midterm Project - by Kim Nguyen
# Docker Compose & Log Management

## Project Overview
This project demonstrates a multi-container system with:

- **Flask backend** thahttps://github.com/kimnguyen2609/midterm_cloudcomputing/tree/maint logs user requests
- **Nginx frontend** serving a static page and reverse proxying API requests
- **Docker Compose** to manage containers, environment variables, mounts, and logs

---

## Project Structure

kimnguyen_midterm_project/
├── backend/
│   ├── app.py
│   └── Dockerfile
├── frontend/
│   ├── index.html
│   └── nginx.conf
├── docker-compose.yml
└── README.md

---

## Prerequisites

- Docker
- Docker Compose
- Linux/macOS/Windows with terminal access

---

## How to Run

1. Clone the repository:

```
git clone <your-github-repo-url>
cd kimnguyen_midterm_project
```

2. Build and start the project:
