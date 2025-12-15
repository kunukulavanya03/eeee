# eeee

Backend API for eeee

## Tech Stack

- **Frontend**: React
- **Backend**: FastAPI + SQLAlchemy
- **Frontend Source**: GitHub ([Repository](https://github.com/Malleswar-249/E-COMMERCE-WEBSITE))

## Project Structure

```
eeee/
├── frontend/          # Frontend application
├── backend/           # Backend API
├── README.md          # This file
└── docker-compose.yml # Docker configuration (if applicable)
```

## Getting Started

### Prerequisites

- Node.js 18+ (for frontend)
- Python 3.11+ (for Python backends)
- Docker (optional, for containerized setup)

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
# Follow backend-specific setup instructions in backend/README.md
```

## Features

- User registration and login
- Password reset
- Profile management
- Resource creation and management

## API Endpoints

- `POST /api/register` - Create a new user account
- `POST /api/login` - Log in to an existing user account
- `POST /api/password_reset` - Reset the password for an existing user account
- `GET /api/profile` - View profile information for the current user
- `PUT /api/profile` - Update profile information for the current user
- `GET /api/resources` - View a list of available resources
- `POST /api/resources` - Create a new resource
- `PUT /api/resources/{id}` - Update an existing resource
- `DELETE /api/resources/{id}` - Delete a resource

## License

MIT
