# Lead Generation Platform

A production-ready lead generation platform with Python FastAPI backend, PostgreSQL database, and Flutter mobile frontend.

## Features

### Core Features
- **User Authentication**: JWT-based authentication with role-based access control
- **Business Management**: Register, verify, and manage businesses
- **Lead Management**: Submit, assign, track, and manage leads
- **Admin Dashboard**: Comprehensive dashboard with analytics and user management
- **Push Notifications**: Real-time notifications for lead updates
- **REST API**: Complete REST API with Swagger documentation

### Roles
- **Admin**: Full platform control, user management, analytics
- **Business**: Lead management, profile management, performance tracking
- **Customer**: Lead submission, lead history tracking

## Tech Stack

### Backend
- FastAPI 0.104.1
- PostgreSQL 15
- SQLAlchemy 2.0
- JWT Authentication
- Pydantic v2
- Pytest
- Alembic (migrations)

### Frontend
- Flutter 3.16+
- Provider (state management)
- Dio (HTTP client)
- Firebase Cloud Messaging
- Shared Preferences

## Quick Start

### Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
alembic upgrade head
uvicorn app.main:app --reload
```

### Frontend
```bash
cd frontend
flutter pub get
flutter run
```

### Docker
```bash
docker-compose up -d
```

## Documentation

- [API Documentation](docs/API.md)
- [Database Schema](docs/DATABASE.md)
- [Deployment Guide](docs/DEPLOYMENT.md)
- [Development Setup](docs/DEVELOPMENT.md)
- [Architecture](docs/ARCHITECTURE.md)

## License

MIT License
