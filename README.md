# Django Vite React Docker Starter
Asset Allocation Project Initialize

## Overview

This is a basic setup for an asset allocation system using Docker. It includes:
- A frontend built with React and Vite.
- A backend built with Django.

## Note on Similarity

While publishing this project, I found that it shares some similarities with [Django React Starter](https://github.com/Jordan-Kowal/django-react-starter) by Jordan Kowal. I highly recommend checking out his project as well – it's a great resource for anyone looking to kickstart a project with Django and React!

## How to Run

1. **Clone the repository**:

```bash
git clone https://github.com/bautsi/django-vite-react-starter.git
```

2. **Navigate to the project directory**:

```bash
cd .\asset-allocation\
```

3. **Build and start the Docker containers**:

```bash
docker-compose up --build
```

4. **The frontend will be available at http://localhost:3000 and the backend at http://localhost:8000.**

## Customization

If you'd like to rename the project, you can do so by renaming the following directories and files:

**To rename the project**:
- Rename the folder asset-allocation to your preferred project name.
- Rename everything called asset_dashboard to your frontend name.
- Rename everything called asset_allocator to your backend name.
