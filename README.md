

# Resume Analyzer

Resume Analyzer is a web application that allows users to upload resumes and get analyzed feedback on their content. The frontend is built with Next.js, while the backend is powered by Django. 

<i> **This project aims to gather skill on how to integrate LLM with Full Stack Web Application.   </i>

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- Upload resumes in various formats (PDF, DOCX, etc.).
- Analyze resumes for content quality, keyword matching, and more.
- Provide feedback and suggestions for improvement.

## Prerequisites

- Node.js
- npm or yarn
- Python
- Django
- PostgreSQL (or any preferred database)

## Installation

### Backend (Django)

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/resume-analyzer-backend.git
    ```

2. Navigate to the backend directory:

    ```sh
    cd resume-analyzer-backend
    ```

3. Create a virtual environment:

    ```sh
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

        ```sh
        venv\Scripts\activate
        ```

    - On macOS/Linux:

        ```sh
        source venv/bin/activate
        ```

5. Install dependencies:

    ```sh
    pip install -r requirements.txt
    ```

6. Run database migrations:

    ```sh
    python manage.py migrate
    ```

7. Start the Django development server:

    ```sh
    python manage.py runserver
    ```

### Frontend (Next.js)

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/resume-analyzer-frontend.git
    ```

2. Navigate to the frontend directory:

    ```sh
    cd resume-analyzer-frontend
    ```

3. Install dependencies:

    ```sh
    npm install
    ```

    or

    ```sh
    yarn install
    ```

4. Start the Next.js development server:

    ```sh
    npm run dev
    ```

    or

    ```sh
    yarn dev
    ```

## Environment Variables

### Backend (Django)

