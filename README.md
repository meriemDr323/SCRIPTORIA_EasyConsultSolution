# SCRIPTORIA - Easy Consult Solution

A full-stack library management web application that allows users to browse, search, and manage library resources efficiently.

## Tech Stack

- **Frontend**: React + Vite
- **Backend**: Laravel (PHP)
- **Database**: SQLite / MySQL
- **Authentication**: Laravel Sanctum

## Project Structure

```
LibraryProject/
├── backend/    # Laravel REST API
└── frontend/   # React application
```

## Getting Started

### Prerequisites

- PHP >= 8.1
- Composer
- Node.js >= 18
- npm

### Backend Setup

```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## Features

- Book catalog browsing and search
- User authentication and authorization
- Library resource management (CRUD)
- Responsive UI

## License

MIT
