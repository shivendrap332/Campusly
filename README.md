Campusly is a comprehensive web-based placement management system designed specifically for college students. Built with the MERN stack, it streamlines placement activities, student data management, and company interactions for the entire batch.

✨ Features

📊 Student Dashboard – Comprehensive profile management and placement status tracking
🏢 Company Management – Detailed company profiles and job posting system
📈 Analytics & Statistics – Visual insights into placement trends and data
👥 User Authentication – Secure JWT-based login with email OTP verification
📧 Email Notifications – Automated updates for placement activities
📱 Responsive Design – Optimized for desktop and mobile devices
🔍 Advanced Filtering – Powerful search and filter capabilities using AG Grid
💼 Experience Sharing – Students can share interview experiences with ratings and tips
👨‍💻 Team Information – Comprehensive developer team profiles and project details
🔒 Role-based Access – Admin and student roles with appropriate permissions

🏗️ Architecture
Campusly/
├── 📁 client/                 # React frontend application
│   ├── 📁 public/             # Static assets
│   └── 📁 src/
│       ├── 📁 api/            # API service layer
│       ├── 📁 components/     # Reusable React components
│       ├── 📁 pages/          # Main application pages
│       ├── 📁 utils/          # Utility functions
│       └── 📄 App.jsx         # Main App component
├── 📁 server/                 # Node.js backend application
│   ├── 📁 controllers/        # Route controllers
│   ├── 📁 middleware/         # Custom middleware
│   ├── 📁 models/             # MongoDB data models
│   ├── 📁 routes/             # API route definitions
│   ├── 📁 utils/              # Backend utilities
│   ├── 📄 seedDatabase.js     # Sample data seeder
│   ├── 📄 testStats.js        # API testing script
│   └── 📄 index.js            # Server entry point
├── 📄 package.json            # Root package configuration
├── 📄 DEVELOPMENT.md          # Development guide
├── 📄 setup.bat               # Windows setup script
├── 📄 setup.sh                # Unix setup script
└── 📄 README.md               # Project documentation
