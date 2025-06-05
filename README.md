Simple Social Clone (Django)
A lightweight social-network project built with Python + Django—perfect for students who want a real-world full-stack codebase without heavy setup.

Key Features
User accounts – sign-up, log-in, log-out via Django auth

Groups – create & join topical communities

Posts feed – newest posts first, Markdown formatting (via misaka)

Clean UI – Bootstrap templates that work on desktop & mobile

Modular design – separate apps (accounts, groups, posts) for clarity

Tech Stack
Layer	Tool/Lib
Backend	Django 4 (SQLite by default)
Frontend	Django templates + Bootstrap 5
Markdown	misaka
Auth	Django built-ins
Deploy-ready	Easy swap to Postgres/MySQL; Docker-friendly

Quick Start
bash
Copy
Edit
# Clone & enter the project
git clone https://github.com/your-user/simple-social.git
cd simple-social

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate       # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
# (or: pip install django misaka)

# Apply migrations
python manage.py migrate

# (Optional) create admin user
python manage.py createsuperuser

# Run the development server
python manage.py runserver
# Visit http://127.0.0.1:8000
Learning Goals
See Django project vs. app layout in practice

Implement CRUD and model relationships (User → Post, Group ↔ User)

Work with class-based views and URL routing

Integrate pagination, Markdown, and Bootstrap in a real app

Extension Ideas
Add comments or likes to posts

Implement pagination for long feeds

Write unit tests for models and views

Containerize with Docker and Postgres

Deploy to Render, Railway, Fly.io, etc.

Contributing
Fork the repo and create a feature branch.

Follow the Quick Start steps.

Add tests if you change logic.

Open a PR with a clear description of your changes.

