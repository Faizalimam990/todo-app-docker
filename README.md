# Flask To-Do Application

This is a simple To-Do application built using Flask. It allows users to add, mark as complete, and delete tasks from their to-do list.

## Set up a Virtual Environment and Install Dependencies

Follow these steps to set up the project on your local machine.

### 1. Create a Virtual Environment

```bash
python -m venv venv
```
### 2. Activate the Virtual Environment

- **Linux/Mac:**

```bash
source venv/bin/activate
```
- **Windows:**
```bash
venv\Scripts\activate
```
### 3. Install Dependencies

Ensure all the required libraries are installed by running:

```bash
pip install -r requirements.txt
```

## Start the Application

To run the application locally, use the following command:

```bash
python app.py


```
## Running with Docker

### 1. Build the Docker Image

```bash
docker build -t flask-todo-app .
```
### 2. Run the Docker Container

```bash
docker run -p 5000:5000 flask-todo-app
```
## Features

```csharp
- Add tasks to your to-do list.
- Mark tasks as complete/incomplete.
- Delete tasks from the list.
