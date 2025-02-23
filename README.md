# Web3Fy

A modern full-stack web application with separate frontend and backend components.

## Project Structure

The project is organized into two main directories:

- `Frontend/`: React-based web application
- `Backend/`: Python-based backend server

## Frontend

The frontend is built using modern web technologies and includes:

- Package management with Yarn
- Modern development tooling and linting
- Organized component structure
- GitHub workflows and Husky for git hooks

### Frontend Setup

1. Navigate to the Frontend directory:
```bash
cd Frontend
```

2. Install dependencies:
```bash
yarn install
```

3. Start the development server:
```bash
yarn dev
```

## Backend

The backend is built with Python and includes:

- RESTful API routes
- Docker support for containerization
- Store management
- Custom agents
- Script utilities

### Backend Setup

1. Navigate to the Backend directory:
```bash
cd Backend
```

2. Set up a Python virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Start the server:
```bash
python main.py
```

### Docker Setup (Optional)

The backend can also be run using Docker:

```bash
docker-compose up --build
```

## Development

- The frontend development server typically runs on `http://localhost:3000`
- The backend API server runs on the port specified in `main.py`
- Use the provided linting and formatting tools to maintain code quality

## Contributing

Please refer to the `CONTRIBUTING.md` file in the Frontend directory for guidelines on contributing to this project.

## License

This project is licensed under the terms specified in the `LICENCE` file in the Frontend directory. 