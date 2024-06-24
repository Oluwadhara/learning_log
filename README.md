# Learning Log

A full-stack web application that allows users to log their learning activities, create topics, and add entries under each topic. Built using Django for the backend and Bootstrap for the frontend.

![learning log2](https://github.com/Oluwadhara/learning_log/assets/99046185/8e6b10a7-e585-46d7-a219-6faa3aeac53f)
![learning log](https://github.com/Oluwadhara/learning_log/assets/99046185/2e7a64ee-a296-498b-88d4-8c3e1ffc4841)

## Features

- User authentication (sign up, log in, log out)
- Create, read, update, and delete topics
- Add, read, update, and delete entries under topics
- Responsive design with Bootstrap
- Secure password hashing and user session management

## Technologies Used

- Django
- Bootstrap
- HTML/CSS
- SQLite (default Django database)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Oluwadhara/learning_log.git
    cd learning_log
    ```

2. **Create a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install dependencies:**
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

7. **Access the application:**
    Open your web browser and go to `http://localhost:8000`

## Usage

1. Sign up for a new account or log in with an existing account.
2. Create a new topic.
3. Add entries under the created topics.
4. View, update, and delete topics and entries as needed.

## Contributing

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or questions, please reach out to Olufemi Oluwadara at olufemioluwadara@gmail.com.

