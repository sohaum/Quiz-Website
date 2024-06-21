# Quiz Website

This repository contains the source code for a Quiz Website project. The website allows users to take quizzes on various topics, providing an interactive and educational experience.

## Overview

The Quiz Website project aims to provide a platform where users can take quizzes, view their scores, and learn from the feedback provided after each quiz. The project includes features such as user authentication, quiz creation, and detailed scoring.

## Features

- **User Authentication**: Secure login and registration system.
- **Quiz Management**: Admins can create, edit, and delete quizzes.
- **Interactive Quizzes**: Users can take quizzes and receive instant feedback.
- **Scoring System**: Users can view their scores and track their progress.
- **Responsive Design**: The website is accessible on both desktop and mobile devices.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/sohaum/Quiz-Website.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Quiz-Website/Quiz_proj v4(Final)
    ```
3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```
4. Set up the database:
    ```sh
    python manage.py migrate
    ```
5. Create a superuser to access the admin panel:
    ```sh
    python manage.py createsuperuser
    ```
6. Run the development server:
    ```sh
    python manage.py runserver
    ```

## Usage

1. Access the website at `http://127.0.0.1:8000/`.
2. Register a new account or log in with an existing account.
3. Take quizzes available on the platform and view your scores.
4. Admins can log in to the admin panel at `http://127.0.0.1:8000/admin/` to manage quizzes and users.

## Dependencies

- Python 3.x
- Django
- Django REST framework
- Other dependencies as listed in `requirements.txt`

You can install the required packages using:
```sh
pip install -r requirements.txt
```

## Contributing
Contributions are welcome! If you have any improvements or new features for the Quiz Website, please feel free to fork the repository, make your changes, and submit a pull request.
