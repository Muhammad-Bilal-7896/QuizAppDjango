# 🚀 Question-Answer Django Admin App

This repository contains a simple question-answer Django admin app that uses SQLite as the database.

## ⚙️ Tech Stack

- Django 🐍 - A high-level Python web framework.
- SQLite 📁 - A lightweight, file-based relational database management system.
- HTML/CSS 🎨 - Front-end technologies for creating user interfaces.

## ✨ Features

- Allows administrators to add, edit, and delete questions and answers.
- Questions and answers are stored in an SQLite database.
- The app provides a user-friendly web interface powered by Django's admin site.

## 🖥️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Muhammad-Bilal-7896/Technical-Test.git
   ```

2. Create and activate a virtual environment:

   ```bash
   python3 -m venv env
   source env/bin/activate
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up the SQLite database:

   ```bash
   python manage.py migrate

## 🛠️ Usage

   1. Start the development server:

      ```bash
      python manage.py runserver
      ```

   2. Open your web browser and navigate to http://localhost:8000/admin/.

   3. Log in with your superuser account or create one using the following command:

      ```bash
      python manage.py runserver
      ```
   4. Once logged in, you can perform the following actions through the Django admin interface:

  - Add questions and answers by clicking on the "Questions" or "Answers" section.
  - Edit existing questions and answers.
  - Delete questions and answers.

## 🤝🏻 Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please create a new issue or submit a pull request.

## 📃 License
This project is licensed under the MIT License.

