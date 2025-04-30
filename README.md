# Python JS AI Voice Agent

## Overview

This project is a full-stack application featuring a Python Flask backend and a React + TypeScript frontend. It demonstrates a simple order management system where users can potentially interact with order data, possibly through a voice interface facilitated by the `@vapi-ai/web` library in the frontend.

## Purpose and Problem Solved

The primary purpose of this project is to showcase the integration between a Python backend API and a modern JavaScript frontend framework (React). It provides a basic example of handling API requests, managing data (in-memory for this example), and structuring a full-stack application. It potentially solves the problem of accessing order information through a web interface, possibly enhanced with voice capabilities.

## Key Features

*   **Backend API:** Flask-based API endpoint (`/orders`) to retrieve order details.
*   **Frontend Interface:** React + TypeScript application built with Vite for a modern user experience.
*   **Order Data Management:** Simple in-memory data storage for orders (`db.py`).
*   **Potential Voice Interaction:** Includes `@vapi-ai/web` library, suggesting potential voice agent capabilities.
*   **Clear Structure:** Separated frontend and backend directories.

## Requirements

### Backend

*   Python 3.x
*   Flask

### Frontend

*   Node.js and npm (or yarn)

## File Structure

```
PythonJSAIVoiceAgent-main/
├── __pycache__/         # Python cache files
├── frontend/             # React frontend application
│   ├── public/           # Static assets
│   ├── src/              # Frontend source code (React components, etc.)
│   ├── .gitignore
│   ├── README.md         # Frontend specific README (Vite template)
│   ├── eslint.config.js  # ESLint configuration
│   ├── index.html        # Main HTML file
│   ├── package.json      # Frontend dependencies and scripts
│   ├── package-lock.json
│   ├── tsconfig.app.json # TypeScript config for app
│   ├── tsconfig.json     # Base TypeScript config
│   ├── tsconfig.node.json# TypeScript config for Node
│   └── vite.config.ts    # Vite configuration
├── api.py                # Flask API definition
├── db.py                 # In-memory order database
├── prompts.txt           # Likely contains prompts for the AI voice agent
└── requirements.txt      # Backend Python dependencies
```

## Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
cd PythonJSAIVoiceAgent-main
```

### 2. Setup Backend

```bash
# Navigate to the root directory if not already there
cd PythonJSAIVoiceAgent-main

# Create a virtual environment (optional but recommended)
python -m venv venv
# Activate the virtual environment
# Windows:
.\venv\Scripts\activate
# macOS/Linux:
# source venv/bin/activate

# Install backend dependencies
pip install -r requirements.txt

# Run the Flask server
python api.py
```

The backend server will typically start on `http://127.0.0.1:5000`.

### 3. Setup Frontend

```bash
# Navigate to the frontend directory
cd frontend

# Install frontend dependencies
npm install

# Start the development server
npm run dev
```

The frontend development server will usually start on `http://localhost:5173` (or another port if 5173 is busy).

### 4. Access the Application

Open your web browser and navigate to the URL provided by the frontend development server (e.g., `http://localhost:5173`).

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues to improve the project.

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature-name`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature/your-feature-name`).
6.  Open a Pull Request.

## Contact

*   **Name:** Syed Abdullah Shah
*   **Email:** [sa.abdullahshah.2001@gmail.com](mailto:sa.abdullahshah.2001@gmail.com)
*   **LinkedIn:** [Syed Abdullah Shah](www.linkedin.com/in/syed-abdullah-shah-4018a5176)
