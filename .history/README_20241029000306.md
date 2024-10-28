# Energy Monitoring System

A comprehensive system for monitoring and analyzing energy consumption using Non-Intrusive Load Monitoring (NILM) techniques.

## Project Structure

- `backend/`: Python FastAPI backend
  - `app/`: Main application code
  - `tests/`: Test files
- `frontend/`: React frontend application
- `docs/`: Project documentation

## Setup Instructions

### Backend Setup
1. Create a virtual environment:
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

### Frontend Setup
1. Install dependencies:
```bash
cd frontend
npm install
```

## Development

### Running the Backend
```bash
cd backend
uvicorn app.main:app --reload
```

### Running the Frontend
```bash
cd frontend
npm start
```

## Contributing

1. Create a new branch for your feature
2. Make your changes
3. Submit a pull request

## License

[Your chosen license]