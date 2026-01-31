# Exam Admin Portal

A comprehensive examination administration portal built with modern web technologies for managing exams, students, and administrative tasks.

## 📋 Project Overview

The Exam Admin Portal is a full-stack application designed to streamline the examination management process. It provides administrators with tools to create, manage, and monitor examinations while offering students a seamless interface for taking tests.

## 🏗️ Project Structure

```
Exam-Admin-Portal/
├── .config/              # Configuration files
├── .git/                 # Git version control
├── .local/               # Local application data
├── client/               # Frontend application
├── node_modules/         # Project dependencies
├── script/               # Utility scripts
├── server/               # Backend application
├── shared/               # Shared resources between client and server
├── .env                  # Environment variables
├── .gitignore           # Git ignore rules
├── .replit              # Replit configuration
├── components.json      # Component definitions
├── drizzle.config.ts    # Drizzle ORM configuration
├── package.json         # Node.js dependencies and scripts
├── package-lock.json    # Locked dependency versions
├── postcss.config.js    # PostCSS configuration
├── tailwind.config.ts   # Tailwind CSS configuration
├── tsconfig.json        # TypeScript configuration
└── vite.config.ts       # Vite build configuration
```

## 🚀 Features

- **User Authentication & Authorization**
  - Secure login system for administrators and students
  - Role-based access control

- **Exam Management**
  - Create and configure examinations
  - Set time limits and question pools
  - Schedule exams

- **Student Management**
  - Register and manage student accounts
  - Track student performance
  - Generate reports

- **Question Bank**
  - Create and organize questions
  - Support for multiple question types
  - Import/export functionality

- **Real-time Monitoring**
  - Live exam supervision
  - Anti-cheating measures
  - Progress tracking

## 🛠️ Technology Stack

### Frontend
- **React/Vite** - Fast, modern build tool and development server
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **PostCSS** - CSS transformation tool

### Backend
- **Node.js** - JavaScript runtime
- **Express** (likely) - Web application framework
- **Drizzle ORM** - TypeScript ORM for database operations

### Database
- Database configuration managed through Drizzle ORM

## 📦 Installation

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Database (PostgreSQL/MySQL/SQLite)

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Exam-Admin-Portal
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure environment variables**
   Create a `.env` file in the root directory and add the following:
   ```env
   DATABASE_URL=your_database_connection_string
   PORT=3000
   JWT_SECRET=your_jwt_secret
   NODE_ENV=development
   ```

4. **Run database migrations**
   ```bash
   npm run db:migrate
   ```

5. **Start the development server**
   ```bash
   npm run dev
   ```

## 🎯 Usage

### For Administrators

1. **Login** to the admin portal
2. **Create Exams** - Set up new examinations with questions and time limits
3. **Manage Students** - Add students and assign them to exams
4. **Monitor Exams** - Track ongoing examinations in real-time
5. **Generate Reports** - View and export examination results

### For Students

1. **Login** with provided credentials
2. **View Available Exams** - See scheduled examinations
3. **Take Exams** - Complete exams within the allocated time
4. **View Results** - Check scores and feedback

## 📜 Available Scripts

```bash
# Development
npm run dev          # Start development server

# Build
npm run build        # Build for production

# Database
npm run db:migrate   # Run database migrations
npm run db:push      # Push schema changes
npm run db:studio    # Open Drizzle Studio

# Linting & Formatting
npm run lint         # Run ESLint
npm run format       # Format code
```

## 🔒 Security Features

- Encrypted password storage
- JWT-based authentication
- CSRF protection
- Input validation and sanitization
- Secure session management

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- Your Name - Initial work

## 🙏 Acknowledgments

- Thanks to all contributors
- Inspired by modern exam management systems
- Built with love for education

## 📞 Support

For support, email support@examadminportal.com or open an issue in the repository.

---

**Note**: This is a development project. Please ensure proper security measures are in place before deploying to production.