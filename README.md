# Django To-Do List Application

## Overview
This project is a web-based To-Do List application built with Django. It allows users to manage their daily tasks with features like adding, editing, and deleting tasks. The app also includes a responsive design for an enhanced user experience.

## Features
- **Task Management**: Add, edit, and delete tasks seamlessly.
- **User Authentication**: Securely manage personal task lists.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Requirements
- Python 3.8 or higher
- Django 3.x or higher
- pip (Python package manager)

## Installation

### Clone the Repository:
1. Clone this repository using:
   ```bash
   git clone https://github.com/your-username/todo-list.git
   cd todo-list
   ```

### Set Up the Environment:
2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

### Install Dependencies:
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Apply Migrations:
4. Set up the database by applying migrations:
   ```bash
   python manage.py migrate
   ```

### Run the Server:
5. Start the development server:
   ```bash
   python manage.py runserver
   ```
6. Open your browser and navigate to:
   ```
   http://127.0.0.1:8000/
   ```

## Usage
1. **Sign Up or Log In**: Access the task management features after signing in.
2. **Add Tasks**: Use the input field to add new tasks.
3. **Edit Tasks**: Update tasks using the edit icon.
4. **Delete Tasks**: Remove completed or unwanted tasks using the delete icon.

## File Structure
- `todo_app/`: Core application containing views, models, and templates.
- `static/`: Contains CSS, JavaScript, and other static assets.
- `templates/`: HTML templates for the application.
- `manage.py`: Django’s command-line utility.

## Customization
- Modify styles in the `static/css/` directory to change the look and feel.
- Update task model fields in `todo_app/models.py` to add more task attributes.

## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make and commit your changes.
4. Push your branch to your fork.
5. Submit a pull request.

## License
This project is licensed under the avhinfotechs License. See the LICENSE file for details.

## Contact
- **Name**: HARINI R
- **Email**: harinirajan@gmail.com

Enjoy managing your tasks with this Django To-Do List application!

