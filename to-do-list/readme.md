
# Flask Todo List App

This Flask Todo List App is a simple yet powerful tool to manage your daily tasks. Built with Flask, it leverages Bootstrap for styling, providing a responsive and intuitive user interface. Users can create, edit, mark as done/undone, and delete todo items with ease.

## Features

- **Create Todo Items:** Add new tasks to your list with a simple input field.
- **Mark Todo Items as Done/Undone:** Easily toggle the status of your tasks to keep track of what's completed.
- **Edit Todo Items:** Update the details of your tasks as needed.
- **Delete Todo Items:** Remove tasks from your list that are no longer needed.
- **Responsive Design:** Utilizes Bootstrap to ensure a great experience on devices of all sizes.

## Requirements

- Python 3.6 or higher
- Flask
- Jinja2
- Bootstrap (included via CDN)

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/flask-todo-list.git
    ```

    Replace `your-username` with your actual GitHub username.

2. **Create and Activate a Virtual Environment:**

    On Windows:
    ```bash
    python -m venv venv
    .\venv\Scripts\activate
    ```

    On Unix or MacOS:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install Required Dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Running the Application

Start the Flask development server:

```bash
python app.py
```

Navigate to `http://127.0.0.1:5000/` in your web browser to access the Todo List App.

## Using the Application

- **Add a Todo Item:** Enter the task in the input field and click "Add".
- **Mark Todo as Done/Undone:** Click the checkbox next to a task to toggle its completion status.
- **Edit a Todo Item:** Click "Edit" next to a task, modify the text, and then save your changes.
- **Delete a Todo Item:** Click "Delete" next to a task you wish to remove.

## Additional Notes

This application is designed as a basic example of a Flask app. It can be extended with more sophisticated features, such as user authentication, database integration, or a richer front-end framework integration.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
