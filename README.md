# Django Blog Site

A feature-rich blog application built with **Django**. Supports user registration, post creation, editing, and commenting—all styled with responsive templates.

---

##  Features

- Author registration and authentication
- Create, edit, and delete blog posts
- Commenting on posts
- User-friendly, responsive design
- Optional: Markdown support, rich-text editing, pagination

---

##  Project Structure (Example)

```plaintext
Django-BLOG-SITE/
├── manage.py
├── requirements.txt
├── .gitignore
├── blogsite/                # Project settings
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── blog/                    # Django app for blog features
│   ├── migrations/
│   ├── templates/blog/
│   │   ├── base.html
│   │   ├── post_list.html
│   │   ├── post_detail.html
│   │   ├── post_form.html
│   │   └── post_confirm_delete.html
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── forms.py
└── static/                  # Static files (CSS, images, JS)
Prerequisites
Python 3.x installed

pip (Python package installer)

Optional: A virtual environment (recommended)

Optional: .env file for sensitive data (e.g., secret keys)

Setup & Installation
Clone the repository

bash
Copy code
git clone https://github.com/Jaivesh8/Django-BLOG-SITE.git
cd Django-BLOG-SITE
Create and activate a virtual environment

bash
Copy code
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
Install dependencies

bash
Copy code
pip install -r requirements.txt
Configure environment variables
If you use any secrets (e.g., DJANGO_SECRET_KEY, email credentials), add a .env file in project root. Example .env file:

env
Copy code
DJANGO_SECRET_KEY=your_secret_key_here
DEBUG=True
Apply database migrations

bash
Copy code
python manage.py migrate
Create a superuser (optional, for admin access)

bash
Copy code
python manage.py createsuperuser
Run the development server

bash
Copy code
python manage.py runserver
Visit http://127.0.0.1:8000/ to view the blog interface.

Usage Overview
Home Page: Lists all blog posts

Post Detail: Click a title to view content and comments

Create Post: Authenticated users can add new posts

Edit/Delete: Manage your own posts

Comments: View and add comments on posts

Example Visuals (Optional)
Include screenshots here, such as:

Blog list page

Post detail with comments

Post creation/editing form

Admin dashboard

Contribution Guidelines
Improvements are welcome! Consider adding:

Pagination of posts

Rich-text editing or Markdown syntax

User profiles and avatars

Tag/categories filter

Social sharing buttons

Custom styling with Bootstrap or Tailwind CSS

Feel free to open an issue or submit a pull request.

License
Distributed under the MIT License. See the LICENSE file for more details.

Contact & Support
Author: Jaivesh
For any questions or feedback, you can open an issue or reach out directly via Git
