# PicStream

A Django-based social media application where users can create posts, like posts & comment on posts. The application supports user registration, login, and profile management.

## Features

- User registration and authentication
- User profile management
- Create, read, update posts and profile.
- Like and comment on posts
- Light/Dark mode toggle

## Demo
Watch a video of the app in action [https://www.loom.com/share/a488cdffd4d447b883066abedeb9fe83?sid=f98d15ad-e366-4ceb-9861-31a976f8ea42].

## Technologies Used

- Python
- Django
- HTML/CSS
- JavaScript
- Tailwind CSS
- SQLite (default database, can be changed to PostgreSQL or any other database supported by Django)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/SocialMediaApp.git
   cd SocialMediaApp
   ```

2. **Create and activate a virtual environment:**
    - On Windows:

    ```bash
    python -m venv env
    .\env\Scripts\activate
    ```

    - On macOS and Linux:

    ```bash
    python3 -m venv env
    source env/bin/activate
    ```
3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```
4. **Apply migrations:**

    ```bash
    python manage.py migrate
    ```
5. **Create a superuser:**

    ```bash
    python manage.py createsuperuser
    ```
6. **Run the development server:**

    ```bash
    python manage.py runserver
    ```
7. **Open the application in your browser:**
    ```bash
    http://127.0.0.1:8000/
    ```

## Usage

1. **Register a new user:**

    - Go to the registration page and create a new user account.
    - After registration, log in using your credentials.

2. **Create a post:**

    - Navigate to the post creation page.
    - Fill in the required details and upload an image.
    - Submit the form to create a post.

3. **Interact with posts:**

    - Like & comment on user's post to interact.

4. **Manage your profile:**

    - Go to the profile edit page to update your profile information and profile picture.

## Contributing
1. Fork the repository.
2. Create a new branch: git checkout -b my-feature-branch.
3. Make your changes and commit them: git commit -m 'Add some feature'.
4. Push to the branch: git push origin my-feature-branch.
5. Submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any questions or feedback, please contact:
Name: Atharva Deokar
Email: atharva.deokar2005@gmail.com