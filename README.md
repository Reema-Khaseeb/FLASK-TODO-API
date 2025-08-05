 ZIP folder link:
 https://drive.google.com/file/d/1j79hKrX77PuHSC5TgHzlZJRVFl3i-S3o/view?usp=sharing

 # Flask Todo API

This project is a simple Todo API built using Python and Flask. It provides endpoints to manage a list of todo items stored in memory.

## Project Structure

```
flask-todo-api
├── app.py            # Main application file that sets up the Flask server
├── requirements.txt  # Lists the dependencies required for the project
└── README.md         # Documentation for the project
```

## Endpoints

### GET /items

- Returns a list of todo items.

### POST /items

- Adds a new item to the list. The request body should contain a JSON object with the item details.

## Setup Instructions

1. Clone the repository or download the project files.
2. Navigate to the project directory.

   ```
   cd FLASK-TODO-API
   ```

3. Create a virtual environment

   ```
   python -m venv venv 
   ```

4. Activate the virtual environment

   ```
   venv\Scripts\activate 
   ```

5. Install the required dependencies using pip:

   ```
   pip install -r requirements.txt
   ```

6. Run the application:

   ```
   python app.py
   ```

   The server will start running locally.

## Performance Analysis
Task Manager is showing Python process using ~0.3% CPU and ~22.6 MB memory while Flask app is running.
