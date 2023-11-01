# quora-assignment

1. Install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

3. Start the development server:

   ```bash
   python manage.py runserver
   ```

## Usage

### User Registration

- Visit the registration page at `/register/`.
- Fill in the registration form with a username, password, and confirmation.
- Click the "Register" button to create your account.

### User Login

- Visit the login page at `/login/`.
- Enter your registered username and password.
- Click the "Login" button to access your account.

### Posting Questions

- Log in to your account.
- Visit the homepage.
- Click the "Ask a Question" button.
- Fill in the question form and click "Ask Question."

### Answering Questions

- Log in to your account.
- Click on a question you want to answer.
- Scroll down to the answer form.
- Fill in your answer and click "Answer."

### Logging Out

- Click the "Logout" link in the navigation bar.

## Project Structure

- `quora_app/` - Django app directory containing views, models, templates, and forms.
- `templates/` - HTML templates for the project.
- `static/` - Static files (CSS, JavaScript, etc.).
- `quora_project/` - Project-level settings and configuration.
- `manage.py` - Django management script.
- `requirements.txt` - List of project dependencies.

## Built With

- Django - Web framework
- HTML/CSS - Front-end presentation
- Python - Programming language
   
