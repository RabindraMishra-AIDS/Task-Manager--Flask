A lightweight web-based Task Manager application built using Flask, designed to help users efficiently manage their daily tasks with simple CRUD operations. This project was developed as a Capstone Project for Semester 5

## Tech Stack

- **Backend:** Python, Flask, SQLAlchemy
- **Frontend:** HTML5, CSS3, Bootstrap, Jinja2 Templates
- **Database:** SQLite (default; can be configured for PostgreSQL/MySQL)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/RabindraMishra-AIDS/Task-Manager--Flask.git
    cd Task-Manager--Flask
    ```

2. **Create a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Initialize the database:**
    - If using SQLite, the database will be created automatically when the app first runs.
    - For other databases, configure accordingly in your Flask app.

5. **Run the development server:**
    ```bash
    flask run
    ```

6. **Open in your browser:**
    - Visit `http://127.0.0.1:5000/`

## Usage

- **Add a Task:** Use the "Add Task" button to create a new task.
- **Edit a Task:** Click "Edit" next to a task to modify its details.
- **Delete a Task:** Click "Delete" to remove a task from the list.
- **Mark Complete/Incomplete:** Toggle the status to keep your list organized.
  
## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.


