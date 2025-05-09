# FaceSwap AI

An AI-powered tool for swapping faces in videos. Built with FastAPI.

## Features

- FastAPI backend server
- Ready for AI-powered face swapping (video/image processing to be added)
- Easy to extend and integrate with frontend

## Getting Started

### Prerequisites

- Python 3.8+
- (Recommended) Virtual environment

### Setup

1. Clone the repository and navigate to the project directory.
2. Create and activate a virtual environment:
    ```
    python -m venv venv
    .\venv\Scripts\activate
    ```
3. Install dependencies:
    ```
    pip install -r backend/requirements.txt
    ```
4. Run the FastAPI server:
    ```
    uvicorn backend.main:app --reload
    ```

### Project Structure