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


## Outputs

### Login Page:

<img width="889" alt="image" src="https://github.com/YERRINATH/quora-assignment/assets/83647996/18b9d176-c888-4dea-9443-9ea093a95325">

### Register Page:
<img width="857" alt="image" src="https://github.com/YERRINATH/quora-assignment/assets/83647996/d31af79d-5a1b-419c-a2d6-551a747415bb">
### Home Page:
<img width="960" alt="image" src="https://github.com/YERRINATH/quora-assignment/assets/83647996/984878b9-60fc-4b6e-9dd8-f9c29fb992a3">
### Adding Question Page:
<img width="960" alt="image" src="https://github.com/YERRINATH/quora-assignment/assets/83647996/33bbc2a1-84d0-4789-a1f4-8fd863d22f56">
### Questions Page:
<img width="960" alt="image" src="https://github.com/YERRINATH/quora-assignment/assets/83647996/30791f67-0b22-486d-b1cb-2afe8bdacfd6">

   
