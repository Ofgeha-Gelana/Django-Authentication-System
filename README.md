Installation
1. Clone the repository to your local machine:
  - git clone https://github.com/-------/django-authentication-system.git
2. Navigate into the project directory:
  - cd django-authentication-system
3. Create a virtual environment (optional but recommended):
  - python -m venv env
4. Activate the virtual environment:
  - .\env\Scripts\activate

Configuration
1. Install dependencies:
  - pip install -r requirements.txt
2. Ensure you have Django installed. If not, you can install it using pip:
  - pip install django
3. Set up the database:
  - python manage.py migrate
4. Create a superuser to access the Django admin panel:
  - python manage.py createsuperuser
5. Start the development server:
  - python manage.py runserver


Visit http://127.0.0.1:8000/admin/ in your web browser and log in with the superuser credentials created earlier.
Here you can manage users and other authentication-related models.

- Login
To login, navigate to http://127.0.0.1:8000/accounts/login/ and enter your username and password.

- Logout
To logout, simply click on the "Logout" link provided after logging in, or visit http://127.0.0.1:8000/accounts/logout/.

- Signup
To sign up for a new account, go to http://127.0.0.1:8000/signup/ and fill in the required details.

 - Password Change
Logged-in users can change their passwords by visiting http://127.0.0.1:8000/password_change/ and following the instructions.

- Password Reset
If you forget your password, you can request a password reset by going to http://127.0.0.1:8000/password_reset/ and providing the necessary information.
