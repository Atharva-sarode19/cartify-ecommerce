# Cartify - Django E-commerce Web Application

A full-stack **Django-based E-commerce Platform** built using **Python, Django, HTML, CSS, Bootstrap, and JavaScript**.

## Features

* User Registration & Login
* Product Listing & Detail Pages
* Dynamic Shopping Cart
* Checkout Workflow
* Order Tracking System
* Product Reviews
* Contact Support Module
* Responsive Modern UI

## Tech Stack

* Python
* Django
* HTML5
* CSS3
* Bootstrap 5
* JavaScript
* SQLite

## Project Structure

## Project Structure

```text
cartify-ecommerce/
│
├── .gitignore                    # Ignored files and folders
├── README.md                     # Project documentation
├── requirements.txt              # Project dependencies
├── manage.py                     # Django management script                     
│
├── OnlineShopping/               # Main Django project configuration
│   ├── __init__.py
│   ├── settings.py               # Django settings
│   ├── urls.py                   # Main URL routing
│   ├── wsgi.py                   # WSGI configuration
│   └── asgi.py                   # ASGI configuration
│
├── shop/                         # E-commerce application
│   ├── __init__.py
│   ├── admin.py                  # Admin panel configuration
│   ├── apps.py                   # App configuration
│   ├── models.py                 # Database models
│   ├── views.py                  # Application views and business logic
│   ├── urls.py                   # App-specific URL patterns
│   ├── inherit.py                # Shared cart and utility functions
│   ├── tests.py                  # Unit tests
│   │
│   ├── templates/                # HTML templates
│   │   ├── base.html
│   │   ├── index.html
│   │   ├── cart.html
│   │   ├── checkout.html
│   │   ├── login.html
│   │   ├── register.html
│   │   ├── product_view.html
│   │   ├── search.html
│   │   ├── tracker.html
│   │   ├── contact.html
│   │   ├── loggedin_contact.html
│   │   └── change_password.html
│   │
│   └── static/                   # Static assets
│       ├── increase.png
│       └── decrease.png
│
├── screenshots/                 # Uploaded screenshots of the website
│   ├── login-page.png
│   ├── register-page.png
│   ├── contactus-page.png
│   ├── home-page.png
│   ├── cart-page.png
│   ├── trackorder-page.png
│   ├── changepassword-page.png
│   ├── admin-page.png
│
└── media/                        # Uploaded product images
```

```text id=
```
