# Django-HTMX Quickstart Template

Welcome to the Django-HTMX Quickstart Template! 🚀 This template is designed to get you up and running quickly with Django, HTMX, Alpine.js, and TailwindCSS for rapid prototyping. Here's how to get started:

## Prerequisites 📋
- Python 3.8 or higher
- pip (Python package manager)

## Setup 🛠️

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/django-htmx-quickstart.git
   cd django-htmx-quickstart
   ```

2. **Create a Virtual Environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Running the App 🏃‍♂️

1. **Initial Setup**:
   ```bash
   python manage.py migrate  # Setup database
   python manage.py createsuperuser  # Create an admin user
   ```

2. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```

   Visit `http://localhost:8000` in your browser to see the app.

## Features 🌟

- **Django**: Robust backend framework.
- **HTMX**: Brings interactivity to your app without writing JavaScript.
- **Alpine.js**: Minimalist JavaScript framework for composing behavior directly in your markup.
- **TailwindCSS**: Utility-first CSS framework for rapid UI development.

## Customization 🎨

Feel free to customize the template to fit your needs. The project structure is intuitive, making it easy to add new features and components.

## Support 🆘

If you encounter any issues or have questions, please file an issue on the GitHub repository.

Happy coding! 💻🎉