# 📚 BookBridge

> Connecting communities through the power of books - A platform to donate and request books for those in need.

## 🌟 Overview

BookBridge is a modern web application designed to bridge the gap between book donors and those who need books. Our platform makes it easy to donate books you no longer need and request books for educational purposes, creating a community-driven ecosystem for knowledge sharing.

## ✨ Features

- **📖 Book Donation**: Submit book donation requests with detailed information about the books
- **📚 Book Requests**: Request books for educational and personal development purposes
- **🔐 User Authentication**: Secure login and signup functionality
- **🎨 Modern UI**: Beautiful, responsive design with glassmorphism effects and smooth animations
- **✨ Interactive Background**: Particle.js animated background for an engaging user experience
- **📱 Responsive Design**: Fully responsive across all devices - desktop, tablet, and mobile

## 🛠️ Technology Stack

### Frontend
- **React** - Modern JavaScript library for building user interfaces
- **React Router** - Client-side routing for single-page application
- **Tailwind CSS** - Utility-first CSS framework for rapid UI development
- **Particles.js** - Lightweight library for creating particle backgrounds

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework (API endpoints)
- **RESTful API** - Standard API architecture

### API Endpoints
- `POST /api/auth/login` - User authentication
- `POST /api/auth/signup` - User registration
- `POST /api/donations` - Submit book donation requests
- `POST /api/requests` - Submit book request forms

## 📁 Project Structure

```
bookbridge/
├── src/
│   ├── components/
│   │   ├── Navbar.js              # Navigation component
│   │   └── ParticleBackground.js  # Animated particle background
│   ├── pages/
│   │   ├── Homepage.js            # Landing page
│   │   ├── About.js               # About page
│   │   ├── DonateBooks.js         # Book donation form
│   │   ├── RequestBooks.js        # Book request form
│   │   ├── Login.js               # User login page
│   │   └── Signup.js              # User registration page
│   ├── App.js                     # Main application component
│   ├── index.js                   # Application entry point
│   └── index.css                  # Global styles and Tailwind utilities
├── server/                        # Backend API server
├── tailwind.config.js             # Tailwind CSS configuration
└── package.json                   # Project dependencies
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Abhinav09-bits/bookbirdge.git
   cd bookbridge
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

### Building for Production

```bash
npm run build
```

This creates an optimized production build in the `build/` directory.

## 🎨 Key Features Breakdown

### Book Donation Flow
1. Fill out donor information (name, email, phone)
2. Provide book details (title, author, genre, condition, quantity)
3. Enter pickup information (address, preferred time)
4. Submit request and receive confirmation

### Book Request Flow
1. User authentication required
2. Enter requester information
3. Specify book requirements (title, subject, purpose)
4. Submit request for review

### Authentication System
- Secure login with email and password
- Password visibility toggle
- Remember me functionality
- Social login options (Google, Facebook)
- Form validation and error handling

## 🎯 Design Philosophy

- **Accessibility First**: Clean, readable interface with proper contrast
- **User Experience**: Intuitive navigation and form validation
- **Performance**: Optimized bundle size and lazy loading
- **Modern Aesthetics**: Glassmorphism effects, gradient text, and smooth animations

## 📱 Responsive Breakpoints

- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👥 Authors

- **Abhinav** - [@Abhinav09-bits](https://github.com/Abhinav09-bits)

## 🙏 Acknowledgments

- Inspired by the need to make education accessible to all
- Built with ❤️ for communities that believe in the power of knowledge sharing
- Thanks to all contributors and supporters of this project

## 📧 Contact

For questions, suggestions, or collaboration opportunities:

- GitHub: [@Abhinav09-bits](https://github.com/Abhinav09-bits)
- Repository: [bookbirdge](https://github.com/Abhinav09-bits/bookbirdge)

---

**Made with 💙 to make a difference, one book at a time.**
