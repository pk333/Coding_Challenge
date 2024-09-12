# Scavenger Coding Challenge

This web application allows users to upload a CSV file, automatically clean it by removing rows with missing values, and download the cleaned CSV file.

## Tech Stack

- **Frontend**: React (TypeScript)
- **Backend**: Python


## Features

- Upload a CSV file.
- Automatically remove rows with missing values.
- Download the cleaned CSV file.

## How to Run the Project

### Backend (FastAPI)

1. Navigate to the `backend` directory.
2. Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   
3. Install dependencies:


    `pip install -r requirements.txt `

4. Run the FastAPI server:

`uvicorn main:app --reload`

5. The backend will be available at http://127.0.0.1:8000.

### Frontend (React)
1. Navigate to the frontend directory.

2. Install dependencies:

`npm install`

3. Run the React app:

`npm start`

The frontend will be available at http://localhost:3000.
