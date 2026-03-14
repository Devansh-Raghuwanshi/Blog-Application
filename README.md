# FastAPI Blog & REST API

A complete, full-featured web application and RESTful API built from the ground up to demonstrate modern Python backend development practices. 

## 🚀 Overview
This project serves as a robust foundation for a social blogging platform, handling both server-side rendered HTML pages and a programmatic JSON API. It is designed with production-ready architecture in mind, including asynchronous route handling, strict data validation, and a secure authentication flow.

Built by **Devansh Singh Raghuwanshi**, a Computer Science and Engineering major, as a core portfolio piece to showcase backend architecture and relational database management.

## ⚙️ Tech Stack
* **Backend Framework:** FastAPI (Python)
* **Database:** PostgreSQL (via SQLAlchemy ORM)
* **Data Validation:** Pydantic
* **Authentication:** JWT (JSON Web Tokens) & Secure Password Hashing
* **Frontend/Templating:** Jinja2, HTML/CSS (Includes seamless Light/Dark mode toggling)
* **Server:** Uvicorn (ASGI)

## ✨ Core Features
* **REST API:** Fully documented JSON endpoints using automatic Swagger UI (`/docs`) and ReDoc (`/redoc`).
* **User Authentication:** Complete registration, login, and JWT-based session management.
* **CRUD Operations:** Create, Read, Update, and Delete functionality for user posts with strict authorization checks.
* **Account Management:** Dynamic user profiles with image upload capabilities.
* **Background Tasks:** Asynchronous email handling for secure password resets.
* **Pagination:** Dynamic loading and fetching of posts to optimize performance.

## 🛠️ Setup & Installation

**1. Clone the repository**
\`\`\`bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
\`\`\`

**2. Create a virtual environment and install dependencies**
\`\`\`bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
\`\`\`

**3. Configure Environment Variables**
Create a `.env` file in the root directory and add your database URIs, secret keys, and email configuration.

**4. Run the application**
\`\`\`bash
fastapi dev main.py
\`\`\`
*The application will be available at `http://localhost:8000`*

## 🔮 Future Enhancements
*(Note: I am actively developing this project. Below are the custom features currently in the pipeline.)*
* **Full-Text Search:** Implement a search bar to filter posts by title and content.
* **Markdown Support:** Allow users to write and render posts using Markdown syntax.
* **Comment System:** Enable authenticated users to leave relational comments on individual posts.
* **Social OAuth Login:** Integrate Google/GitHub single sign-on (SSO) capabilities.

---
*This repository is actively maintained and continuously updated with new features and optimizations.*